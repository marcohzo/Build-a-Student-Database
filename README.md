
# SQL Database Student Project

This repository contains the code and scripts used for a student database project, created as part of a **140-lesson course**. Throughout this project, we learned how to manage databases using **PostgreSQL** and how to interact with them using **Bash scripts** and SQL commands.

## Project Description

In this project, we created a database to manage information about computer science students. The goal was to develop a **Bash script** that would use **SQL** commands to insert, update, and delete student records in a PostgreSQL database. Throughout the project, we covered key concepts such as:

- **Database and table creation**: We defined the structure of our database, including tables to store student, course, and major information.
- **Using SQL**: We implemented SQL queries to insert, update, delete, and query data, working with integrity constraints like primary and foreign keys.
- **Automation with Bash**: We developed a Bash script that executes SQL commands from files, making it easier to manage the database directly from the terminal.

## Tools Used

- **PostgreSQL**: Relational database management system.
- **Bash**: Scripting language for automating tasks in the terminal.
- **SQL**: Language used to interact with the database (queries, insertions, updates, deletions, etc.).

## Script Features

The Bash script includes several commands to manipulate the database, such as:

- **Create and set up the database**: The script creates the database and the necessary tables to store student information.
- **Insert records**: SQL commands are used to insert student, course, and major information into the tables.
- **Delete and update records**: Through `DELETE` and `UPDATE` commands, the script allows modifying or deleting specific records in the database.
- **Run SQL from files**: The script allows executing multiple SQL commands stored in `.sql` files, which facilitates automation and query reuse.

## Workflow

1. **Initial setup**: We created the database in PostgreSQL and defined the structure of the necessary tables (`students`, `majors`, `courses`).
2. **Running the script**: The Bash script contains instructions to insert data into the tables using SQL queries.
3. **Data manipulation**: Using SQL commands, we manipulate data in the database, including inserting new records, deleting or updating existing data, and running queries to retrieve information.
4. **Automation**: The script automatically runs all queries, simplifying database management without manual intervention.

## SQL Commands Learned

During this project, we worked with the following SQL commands:

- **`CREATE DATABASE` and `CREATE TABLE`**: To create the database and necessary tables.
- **`INSERT INTO`**: To insert new student, course, and major records.
- **`SELECT`**: To query data stored in the tables.
- **`UPDATE` and `DELETE`**: To modify or delete records.
- **`TRUNCATE`**: To quickly remove all records from a table (using `CASCADE` when necessary).
- **`ALTER TABLE`**: To modify the structure of tables (e.g., adding new columns or constraints).

## Running the Script

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/sql-student-project.git
   ```

2. Make sure you have PostgreSQL installed on your machine. If you haven't done so yet, follow [these instructions](https://www.postgresql.org/download/) to install it.

3. Create the database in PostgreSQL (if you haven't already):

   ```bash
   psql -U postgres -c "CREATE DATABASE students;"
   ```

4. Run the Bash script:

   ```bash
   bash script.sh
   ```

   The script will execute the SQL queries and manipulate the database as defined.

## Contributing

This repository is intended for educational purposes, but if you would like to contribute or make improvements, feel free to open a pull request!
