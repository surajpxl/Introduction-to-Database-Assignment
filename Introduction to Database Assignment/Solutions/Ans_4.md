4. Explain 5 challenges of file-based storage system which were tackled by DBMS.

Answer=> File-based system: The same data may be stored in multiple places leading to duplication.
DBMS: DBMS uses normalization to organize data efficiently, eliminating redundancy.
Data Integrity:

File-based system: Data integrity is harder to enforce, and inconsistencies may arise across files.
DBMS: DBMS enforces data integrity through constraints (like primary keys, foreign keys) and transactional control.
Data Security:

File-based system: Security is not centralized; files are managed at the operating system level with limited access control.
DBMS: DBMS allows for robust security mechanisms, including user authentication and role-based access control.
Data Access and Retrieval:

File-based system: Accessing and retrieving data from files can be slow and inefficient.
DBMS: DBMS uses indexing and query optimization to improve access time and retrieval efficiency.
Concurrency Control:

File-based system: Multiple users accessing the same file may lead to conflicts, corruption, or data inconsistency.
DBMS: DBMS provides concurrency control mechanisms (transactions, locks, isolation levels) to ensure consistency when multiple users access the data simultaneously.