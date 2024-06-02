<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Database Management Systems</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 40px; line-height: 1.6; }
        h1, h2 { color: #333; }
        .container { max-width: 800px; margin: 0 auto; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Database Management Systems</h1>
        
        <h2>Relational Database Management Systems (RDBMS)</h2>
        <p>
            <strong>Characteristics:</strong>
            <ul>
                <li>Structured Data: Data is organized in tables (relations) consisting of rows and columns.</li>
                <li>Schema-Based: Requires a fixed schema defining the structure of the data.</li>
                <li>SQL: Uses Structured Query Language (SQL) for defining and manipulating data.</li>
                <li>ACID Transactions: Ensures Atomicity, Consistency, Isolation, and Durability (ACID) properties for reliable transactions.</li>
            </ul>
        </p>
        
        <p>
            <strong>Examples:</strong>
            <ul>
                <li>MySQL: An open-source RDBMS widely used for web applications.</li>
                <li>PostgreSQL: An open-source RDBMS known for its advanced features and compliance with SQL standards.</li>
                <li>Oracle Database: A commercial RDBMS known for its robustness and scalability.</li>
                <li>Microsoft SQL Server: A commercial RDBMS widely used in enterprise environments.</li>
            </ul>
        </p>
        
        <p>
            <strong>Use Cases:</strong>
            <ul>
                <li>Applications requiring complex queries and transactions, such as financial systems, ERP systems, and CRM systems.</li>
                <li>Environments where data integrity and consistency are critical.</li>
            </ul>
        </p>

        <h2>NoSQL Database Management Systems</h2>
        <p>
            <strong>Characteristics:</strong>
            <ul>
                <li>Flexible Schema: Can handle unstructured, semi-structured, or structured data with flexible or dynamic schema definitions.</li>
                <li>Diverse Data Models: Includes various types such as document-based, key-value stores, column-family stores, and graph databases.</li>
                <li>Scalability: Designed to scale horizontally, making them suitable for large-scale distributed data environments.</li>
                <li>Eventual Consistency: Often prioritizes availability and partition tolerance over immediate consistency (as per the CAP theorem).</li>
            </ul>
        </p>
        
        <p>
            <strong>Types and Examples:</strong>
            <ul>
                <li>Document-Based: Stores data in document formats (e.g., JSON, BSON). Example: MongoDB.</li>
                <li>Key-Value Stores: Simple storage for key-value pairs. Example: Redis, DynamoDB.</li>
                <li>Column-Family Stores: Stores data in columns rather than rows. Example: Apache Cassandra, HBase.</li>
                <li>Graph Databases: Stores data in graph structures with nodes, edges, and properties. Example: Neo4j.</li>
            </ul>
        </p>
        
        <p>
            <strong>Use Cases:</strong>
            <ul>
                <li>Applications requiring high scalability and flexibility, such as social networks, real-time analytics, and content management systems.</li>
                <li>Situations where the data structure may evolve over time or is not strictly defined, such as IoT data or user-generated content.</li>
            </ul>
        </p>

        <h2>Comparison</h2>
        <p>
            <strong>Data Model:</strong>
            <ul>
                <li><strong>RDBMS:</strong> Structured tables with predefined schemas.</li>
                <li><strong>NoSQL:</strong> Flexible, diverse data models (document, key-value, column-family, graph).</li>
            </ul>
        </p>
        
        <p>
            <strong>Scalability:</strong>
            <ul>
                <li><strong>RDBMS:</strong> Vertical scaling (adding more power to existing hardware).</li>
                <li><strong>NoSQL:</strong> Horizontal scaling (adding more machines).</li>
            </ul>
        </p>
        
        <p>
            <strong>Consistency:</strong>
            <ul>
                <li><strong>RDBMS:</strong> Strong consistency with ACID transactions.</li>
                <li><strong>NoSQL:</strong> Eventual consistency, with some providing options for strong consistency.</li>
            </ul>
        </p>
        
        <p>
            <strong>Query Language:</strong>
            <ul>
                <li><strong>RDBMS:</strong> SQL.</li>
                <li><strong>NoSQL:</strong> Varies by database type (e.g., MongoDB uses a query language similar to JSON, Cassandra uses CQL).</li>
            </ul>
        </p>
    </div>
</body>
</html>
