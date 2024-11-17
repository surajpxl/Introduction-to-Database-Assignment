5. List out the different types of classification in DBMS and explain them in depth.

Answer=> Types of Classification in DBMS:

Hierarchical Model:

Data is stored in a tree-like structure with parent-child relationships (one-to-many).
Example: A university database where departments are the parent nodes and courses offered are child nodes under each department.
Pros: Simple, fast access for well-defined structures.
Cons: Inflexible, as data relationships are predefined and hierarchical, making it hard to restructure or query beyond parent-child relationships.
Network Model:

More flexible than the hierarchical model, allowing many-to-many relationships. Data is represented as a graph with nodes and connections.
Example: A banking system where customers can have multiple accounts, and each account can have multiple transactions.
Pros: Can represent more complex relationships.
Cons: Complex structure and difficult to navigate compared to the hierarchical model.
Relational Model:

Data is stored in tables (relations), and each table has rows (tuples) and columns (attributes).
Example: A customer and order table in an e-commerce database, where the customer table contains customer details and the order table contains order information.
Pros: Easy to understand and use, supports powerful querying through SQL.
Cons: Performance can degrade with very large datasets, and relationships can become complex with many tables.
Object-Oriented Model:

Data is stored as objects, similar to object-oriented programming (OOP) concepts. Each object represents an entity and contains both data and methods.
Example: A multimedia database where each media file (video, image, audio) is an object that stores attributes (size, type) and behaviors (play, edit).
Pros: Useful for complex data types like images and videos.
Cons: Can be harder to implement and requires specialized systems.
Document Model:

Data is stored in a document format (JSON, XML, BSON), typically used in NoSQL databases.
Example: A social media database where user posts, comments, and likes are stored as documents.
Pros: Highly flexible and allows for unstructured or semi-structured data.
Cons: Less powerful query mechanisms compared to relational models.