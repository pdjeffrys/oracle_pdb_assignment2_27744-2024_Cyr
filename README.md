

# Assignment Overview

The objective of this assignment was to gain practical experience with Oracle Multitenant Architecture by creating and managing Pluggable Databases (PDBs). The assignment also involved creating database users, assigning privileges, managing temporary PDBs, accessing Oracle Enterprise Manager (OEM), and documenting the entire practical work using GitHub.

# Oracle Environment

* **Oracle Version:** Oracle Database 21c Express Edition (XE)
* **Operating System:** Windows 10
* **Development Tools:**
  * SQL*Plus
  * GitHub

# Task 1: Create and Configure a Pluggable Database

A new Pluggable Database named **cy_pdb_277442024** was successfully created.

The PDB was opened successfully and verified using Oracle SQL commands.

Inside the PDB, a new user named **cyr_plsqlauca_277442024** was created with the password **cyr1234**.

The required privileges were granted to allow the user to connect to the database and perform database operations.

Finally, a successful login was performed using the newly created user to verify that the configuration was correct.

# Task 2: Temporary PDB Creation and Deletion

A temporary Pluggable Database named **cy_to_delete_pdb_277442024** was created successfully.

The existence of the PDB was verified using Oracle commands.

After verification, the temporary PDB was opened and then completely removed using the Oracle DROP PLUGGABLE DATABASE command with the INCLUDING DATAFILES option.

A final verification confirmed that the temporary PDB had been deleted successfully.


# Task 3: Oracle Enterprise Manager (OEM)


# Challenges and Solutions

During this assignment, several challenges were encountered.

One common issue was insufficient privileges when creating or managing the Pluggable Database. This problem was solved by connecting as **SYSDBA** and executing the required administrative commands from the **CDB$ROOT** container.

Another issue involved connecting with the newly created user. This was resolved by granting the required privileges, including **CREATE SESSION**, and ensuring that the connection was made inside the correct Pluggable Database.


# lesson

I learned how to:

* Create and manage Pluggable Databases (PDBs).
* Create Oracle database users.
* Grant user privileges.
* Connect to different database containers.
* Delete PDBs safely.
* Use Oracle Enterprise Manager for database administration.
* Document database administration activities using GitHub.

# Integrity Statement

I confirm that this assignment represents my own practical work, screenshots, and documentation. All external resources consulted have been properly acknowledged.
