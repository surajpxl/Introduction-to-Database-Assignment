7. Explain 3-schema architecture along with its advantages.

Answer=> The 3-schema architecture is a framework for database systems that separates the database into three levels to provide data abstraction and improve data independence.

Internal Schema (Physical Level):

Describes how the data is physically stored in the database. It deals with the file organization and indexing mechanisms.
Example: How tables are stored on the disk, data compression techniques, or how indexes are maintained.
Conceptual Schema (Logical Level):

Describes the logical view of the entire database, focusing on the relationships among data elements. It does not concern itself with how the data is stored.
Example: ER diagrams and logical relationships between entities like "Customer" and "Order."
External Schema (View Level):

Describes how individual users or groups of users view the data. Different users can have different external schemas.
Example: A user interface