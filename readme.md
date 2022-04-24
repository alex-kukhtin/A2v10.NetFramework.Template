
### Getting started

To run this application:

1. Build solution (Ctrl + Shift + B)
2. Create database with any name
3. Run sql-script `~/App_application/sqlscripts/mainapp.sql`
4. Open Web.config and fix the Default connection string (line 4)
     - Data Source: your SqlServer name (`localhost` or `localhost\INSTANCE_NAME` for local SQL Server)
     - Initial Catalog: your database name (from step 1)
5. Run Application without debugging (Ctrl + F5)
6. Login: `admin@admin.com` Password: `Admin`
