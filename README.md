<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            box-sizing: border-box;
        }
        body{
            font-family: Arial;
            padding: 10px;
            background: #f1f1f1;
        }
        /*Header/Blog Title*/
        .Header{
            background: url(j.jpeg);
            padding: 30px;
            text-align: center;
        }
        .Header h1 {
            font-size: 50px;
        }
        /*style the top navigation bar*/
        .topnav { 
            overflow: hidden;
            background-color: #333333; 
        }
        .but {
    
        overflow: hidden;
        background-color: #333333; 
       }
        
        /*style topnav links*/
        .topnav a {
            float: left;
            display: block;
            color: #f3f3f3;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;       
        }
        .but a {
            float: left;
            display: block;
            color: #f3f3f3;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;       
        }

        .topnav:link {
            color:aquamarine
        }
        .but:link {
            color:aquamarine
        }
        /*change color on hover*/
        .topnav a:hover {
            background-color: #dddddd;
            color: #12337a;
        }
        .but a:hover {
            background-color: #dddddd;
            color: #12337a;
        } 
    /*create two unequal colomns that floats next to each other*/
    /*left coloumn*/
    .left column*/
    .leftcolumn {
        float: left;
        width: 75%;
    }
    /*Right column*/
    .Rightcolumn {
        float: left;
        width: 25%;
        background-color: #f1f1f1;
        padding-left: 20px;
    }
    /*fake image*/
    .faking {
        background-color: #aaa;
        width: 100%;
        padding: 20px;
    }

    .suman {
        background-color: #aaa;
        width: 100%;
        padding: 20px;
    }

    /*Add a card effect for articles*/
    .card {
        background-color: white;
        padding: 20px;
        margin-top: 20px;
    }
    /*Clear floats after the columns*/
    .row:after {
        content: "";
        display:table;
        Clear: both;
    }
    /*footer*/
    .footer {
        padding: 20px;
        text-align: center;
        background: #ddd;
        margin-top: 20px;
    }
    /*Responsive layout-when the screen is less than 800px wide, make the two columns
     stack on top of each other instead of next to each other*/
     @media screen and (max-width: 800px) {
         .leftcolumn, .Rightcolumn {
             width: 100;
             padding: 0;
         }         
     }
     /*responsive layout-when the screen is less than 400px wide, ,make the navigation links
     stack on top of each other instead of next to each other*/
     @media screen and (max-width: 400px ) { 
         .topnav a {
        float: none;
        width: 100%;
     }
} 
button{
    weight:50px;
    height: 50px;
    
}
button :hover{
    color: turquoise;
    
}
    </style>
</head>
<body>
    <div class="Header">
        <h1>axmed maxamed ismaaciil aadan yuusuf  </h1>
        <p>Resize the browser window to see the effect</p>
    </div>
    <div class="topnav">
        <a href="#">Link</a>
        <a href="registration.html">Link</a>
        <a href="Table.html"target="_blank">Link</a>
        <div class="but">
   <button a href="#"style="float:Right">Link</a></button>
</div>
    </div>
    <div class="row">
        <div class="leftcolumn">
          <div class="card">
              <h2>TITTLE HEADING</h2>
              <h5>title description,Dec 7,2017</h5>
              <div class="suman" style="height: 200px;"><p> image</p><img src="image/ssss.png" alt=""></div>
              <p>Some text..</p>
              <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur
                  adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                  enim ad minim veniam, quis nostrud exercitation ullamco</p>
          </div>
          <div class="card">
              <h2>TITTLE HEADING</h2>
              <h5>Title description, Sep 2, 2017</h5>
              <div class="faking" style="height: 200px;">
                <p>Some text</p>
                <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur
                    adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                    enim ad minim veniam, quis nostrud exercitation ullamco</p>
              </div>
          </div>
          <div class="rightcolumn">
              <div class="card">
                  <h2>About Me</h2>
                  <div class="faking" style="height: 200px;"><p>image </p><img src="image/ssss.png" alt=""></div>
                  <p>Some text about me im culpa qui officia deserunt mollit anim..</p>
              </div>
              <div class="card">
                  <h3>Popular Post</h3>
                  <div class="faking"><p>Post</p> <img src="image/su.jpg" alt=""></div>
                  <div class="faking"><p>Post</p><img src="image/sn.PNG" alt=""></div>
                  <div class="faking"><p>Post</p><img src="image/ssss.png" alt=""></div>
              </div>
              <div class="card">
              <h3>Follow Me</h3>
              <p>Some text..</p>
              </div>
          </div>
        </div>
        <div class="footer">
            <h2>Footer</h2>
        </div>
</body>
</html>
