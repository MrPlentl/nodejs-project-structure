# `/database`

This directory contains all database-related logic and configuration.

### Structure
- **`/connectors`** — Contains code for connecting to databases (e.g., SQLite, PostgreSQL).  
- **`/migrations`** — Holds migration files used to manage schema changes.  
- **`/models`** — Contains data model classes or ORM models representing database tables.  
- **`/seeders`** — Includes scripts for populating the database with test or initial data.

### Notes
If using SQLite, database files are stored in `/storage/database`.
