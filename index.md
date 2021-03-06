# Welcome to my blog

Visulate for Oracle is a data dictionary browsing application to help data engineers understand the structure and dependencies in Oracle databases that they plan to migrate to the Cloud.

Users supply read-only connection details for one or more the databases. Visulate queries the data dictionary for each connection. Results can be viewed via a browser based UI or REST API calls. Interactive reports are generated for each database object by querying the appropriate dictionary views (e.g. DBA_TABLES and other views for table objects or DBA_SOURCE for packages)

This report also queries database's dependency model to identify dependencies to and from the object (e.g a view "uses" the tables it is based on and is "used by" a procedure that selects from it).
