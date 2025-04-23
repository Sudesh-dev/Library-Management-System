# ⚙️ Setup Instructions

### 1. 📥 Clone the Repository

```bash
git clone https://github.com/Sudesh-dev/Library-Management-System.git
```
### 2. 📂 Open the Project
- Open the folder in NetBeans or your preferred Java IDE.
- In NetBeans, go to File > Open Project, and select the folder you just cloned.

### 3. 🛠️ Configure the Database
- Create a database in MySQL named library.
- Open MySQL or your MySQL client and run the following command to create the database:
```
CREATE DATABASE library;
```
- Import the provided library.sql file to set up the tables and sample data.

- Open your MySQL client and run the following command to import the schema:
```
SOURCE path/to/library.sql;
```
- If you're using a MySQL Workbench, you can also directly execute the SQL file by navigating to "File > Open SQL Script" and selecting the `library.sql` file.


### 4. ▶️ Run the Project
Compile and run the main file (likely Main.java or similar) to launch the application.

- Open NetBeans or your preferred IDE and run the main class (e.g., Main.java).
- In NetBeans, you can run the project by right-clicking on the project and selecting "Run".
