# SQL Murder - Investigating the Crime

This is a group practice project where we investigate a murder that took place in **SQL City**. The goal is to apply basic SQL concepts to work with a database model and solve the case step by step.

## Overview

In this project, you will investigate a murder by executing SQL queries on a database and resolving the case with the same queries provided by the **SQL City** interactive web game.

The game, created by **Joon Park and Cathy He**, is a fun mystery-solving experience, and it provides an interactive SQL query interpreter that you can use to practice SQL queries. After playing the game and solving the case through the web, you will replicate the queries used in the game on a local database (provided in the `data` directory).

Your task is to run the queries, retrieve the necessary information, and use it to resolve the case. The final deliverable will be a Jupyter notebook containing your queries and results, along with an analysis of how each query contributed to solving the crime.

---

## Requirements

- **Python (version 3.x)**: Ensure that Python is installed on your system.
- **Jupyter Notebook**: This will be used to document the queries and results.
- **SQL Database**: The data for SQL City is included in the `data` directory. You will need a working SQL engine to interact with the database (e.g., SQLite, MySQL, PostgreSQL).
- **Libraries**:
  - `sqlite3` or other appropriate SQL connector for the database
  - `pandas` (optional, for easy data manipulation and display)

---

## Steps to Solve the Case

1. **Understand the Data Model**:

   - Review the **SQL City schema** to familiarize yourself with the database structure. This will help you navigate the database and find the necessary information to solve the crime.

2. **Start the Investigation**:

   - Begin by querying the police department's database to retrieve the **crime scene report** related to the murder that occurred on **Jan. 15, 2018** in **SQL City**.

3. **Replicate Queries from the Game**:

   - After solving the case through the interactive web game, replicate the SQL queries in a Jupyter Notebook to get the same results from the local database. Document each query and explain how it helps solve the case.

4. **Presentation**:
   - Prepare a short presentation (5 minutes max) summarizing your findings, queries, and the final resolution of the case.

---

## Data Model

The database schema consists of several tables, which are used to store information about the crime scene, suspects, and events. Here's a quick overview:

![SQL City Schema](attachment:sql_game_schemma.png)

---

## Deliverables

1. **Jupyter Notebook (`SQL_Murder_Investigation.ipynb`)**:

   - Contains all SQL queries used to solve the crime.
   - Each query should be followed by an explanation of its purpose and the result obtained from running it.
   - Conclusions drawn from the queries should be summarized at the end of the notebook.

2. **Presentation**:
   - A brief presentation of the investigation process and final findings (up to 5 minutes).

---

## Installation

If you're setting up the project on your local machine, you can follow these steps:

1. Clone the repository or download the project files.
2. Set up the necessary Python environment:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:

```bash
 jupyter notebook SQL_Murder_Investigation.ipynb
```

4. Make sure to use the appropriate SQL database connector for your environment (SQLite, MySQL, etc.).

## License

This project is based on the SQL Murder game by Joon Park and Cathy He. All rights to the original game and content are reserved by the creators.
