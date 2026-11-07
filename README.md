# 🎓 University Course Management System

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=University+Course+Management+System;SQL+Database+Design+%26+Management;Exploring+Advanced+SQL+Concepts;Turning+Data+Into+Insights" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/SQL-Database-blue?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Database-Relational-4479A1?style=for-the-badge" />
<img src="https://img.shields.io/badge/Project-Final_Practical-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />

<br/><br/>

**A practical SQL database project for managing university students, courses, instructors, departments, and enrollments.**

<br/>

[📂 Repository](https://github.com/PalAnghan/SQL-Final-Project) • [🎥 Video Demo](#-project-video-demonstration) • [🛠️ Features](#-key-features)

</div>

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Project Objectives](#-project-objectives)
- [Video Demonstration](#-project-video-demonstration)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Database Structure](#-database-structure)
- [Project Architecture](#-project-architecture)
- [Project Structure](#-project-structure)
- [SQL Queries](#-sql-queries-implemented)
- [Installation](#-installation--setup)
- [Learning Outcomes](#-learning-outcomes)
- [Future Improvements](#-future-improvements)
- [Developer Profile](#-developer-profile)

---

## 🚀 About the Project

The **University Course Management System** is a relational database project developed as part of my final practical examination.

The project focuses on designing and implementing a structured university database using SQL.

It manages information about students, courses, instructors, departments, and student enrollments.

Through this project, I implemented 16 practical SQL tasks covering database management, CRUD operations, joins, aggregate functions, subqueries, date functions, string functions, window functions, and conditional expressions.

The main goal was to strengthen my practical understanding of SQL and relational database management.

## 🎯 Project Objectives

- Design a structured relational database.
- Create and manage five interconnected tables.
- Store and organize university information.
- Implement CRUD operations on all tables.
- Retrieve information using SQL queries.
- Establish primary key and foreign key relationships.
- Practice intermediate and advanced SQL concepts.
- Generate meaningful insights from database records.

---

## 🎥 Project Video Demonstration

<div align="center">

<img src="https://img.shields.io/badge/Google_Drive-Project_Video_Demo-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" />

### 📽️ Complete Project Walkthrough

**Video demonstration coming soon!**

I will upload my project explanation and practical demonstration to Google Drive.

The video will cover:

1. Database creation.
2. Table creation and relationships.
3. Sample data insertion.
4. CRUD operations.
5. Execution of all 16 SQL queries.
6. Advanced SQL concepts and their outputs.

<br/>

[📂 Watch Project Video on Google Drive](https://drive.google.com/file/d/1BY2k-r6UNTxRiEO0V3WBZnyBD4jHH5j8/view?usp=sharing)

</div>


---

## ✨ Key Features

### 🗄️ Database Management
- Relational database design.
- Five interconnected database tables.
- Primary key and foreign key relationships.
- Structured sample data.
- Data insertion, retrieval, modification, and deletion.

### 👨‍🎓 Student Management
- Store student personal information.
- Retrieve student records.
- Filter students using enrollment dates.
- Track student course enrollments.
- Identify students enrolled in multiple courses.

### 📚 Course Management
- Manage university course information.
- Connect courses with academic departments.
- Calculate average course credits.
- Analyze course enrollment counts.
- Identify courses with high student enrollment.

### 👨‍🏫 Instructor Management
- Store instructor information.
- Retrieve instructor records.
- Combine instructor names.
- Analyze instructor salaries.
- Find maximum salaries by department.

### 📊 SQL Analytics
- Department-wise student counting.
- Course-wise enrollment analysis.
- Aggregate calculations.
- Subquery-based filtering.
- Running total calculations.
- Conditional student classification.

### 🔄 CRUD Operations

| Operation | SQL Command | Description |
|---|---|---|
| Create | INSERT | Add new records |
| Read | SELECT | Retrieve records |
| Update | UPDATE | Modify records |
| Delete | DELETE | Remove records |

CRUD operations are implemented across all five database tables.

---

## 🛠️ Technology Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=mysql,vscode,git,github" alt="Technology Stack" />

</div>

| Technology | Purpose |
|---|---|
| SQL | Database queries and operations |
| MySQL / SQL database environment | Database development and execution |
| Visual Studio Code | SQL development environment |
| Git | Version control |
| GitHub | Project hosting and documentation |

---

## 🏗️ Database Structure

The project contains five main relational tables.

| Table | Description |
|---|---|
| Students | Stores student information |
| Courses | Stores course details |
| Instructors | Stores instructor information |
| Enrollments | Connects students with courses |
| Departments | Stores academic department details |

### 🔗 Table Relationships

```text
                  Departments
                 /           \
                /             \
           Courses          Instructors
              |
              |
          Enrollments
              |
              |
           Students
```

**Relationship overview:**

- Departments → Courses: One-to-Many
- Departments → Instructors: One-to-Many
- Students → Enrollments: One-to-Many
- Courses → Enrollments: One-to-Many

The Enrollments table connects Students and Courses.

---

## 📂 Project Architecture

```text
SQL-Final-Project/
│
├── database/
│   ├── 01_create_database.sql
│   ├── 02_create_tables.sql
│   └── 03_insert_data.sql
│
├── queries/
│   ├── 01_crud_operations.sql
│   ├── 02_students_after_2022.sql
│   ├── 03_mathematics_courses.sql
│   ├── 04_course_enrollment_count.sql
│   ├── 05_students_both_courses.sql
│   ├── 06_students_either_course.sql
│   ├── 07_average_credits.sql
│   ├── 08_max_instructor_salary.sql
│   ├── 09_department_student_count.sql
│   ├── 10_inner_join.sql
│   ├── 11_left_join.sql
│   ├── 12_subquery.sql
│   ├── 13_extract_year.sql
│   ├── 14_concatenate_names.sql
│   ├── 15_running_total.sql
│   └── 16_case_expression.sql
│
└── README.md
```

---

## 💻 SQL Queries Implemented

This project includes 16 practical SQL tasks.

| No. | SQL Concept | Implementation |
|---:|---|---|
| 01 | CRUD Operations | INSERT, SELECT, UPDATE, DELETE |
| 02 | WHERE & Date Filtering | Students enrolled after 2022 |
| 03 | JOIN & LIMIT | Courses offered by Mathematics department |
| 04 | GROUP BY & HAVING | Courses with more than 5 students |
| 05 | GROUP BY & HAVING | Students enrolled in both courses |
| 06 | IN & JOIN | Students enrolled in either course |
| 07 | AVG() | Average credits of all courses |
| 08 | MAX() & JOIN | Maximum instructor salary |
| 09 | COUNT() & GROUP BY | Students enrolled in each department |
| 10 | INNER JOIN | Students and corresponding courses |
| 11 | LEFT JOIN | All students and their courses |
| 12 | Subquery | Students in courses with more than 10 students |
| 13 | YEAR() | Extract enrollment year |
| 14 | CONCAT() | Combine instructor first and last names |
| 15 | Window Functions | Calculate running enrollment totals |
| 16 | CASE WHEN | Classify students as Senior or Junior |

### 📚 SQL Concepts Practiced

**Basic SQL**
- SELECT
- INSERT
- UPDATE
- DELETE
- WHERE
- ORDER BY
- DISTINCT
- LIMIT

**Aggregate Functions**
- COUNT()
- SUM()
- AVG()
- MAX()
- MIN()

**Joins**
- INNER JOIN
- LEFT JOIN

**Advanced SQL**
- GROUP BY
- HAVING
- Subqueries
- Window Functions
- OVER()
- CASE WHEN

**Date and String Functions**
- YEAR()
- MONTH()
- DAY()
- CONCAT()

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/PalAnghan/SQL-Final-Project.git
```

### 2. Navigate to the Project Folder

```bash
cd SQL-Final-Project
```

### 3. Open in Visual Studio Code

```bash
code .
```

### 4. Create the Database

Open and execute:

```text
database/01_create_database.sql
```

### 5. Create the Tables

Execute:

```text
database/02_create_tables.sql
```

### 6. Insert Sample Data

Execute:

```text
database/03_insert_data.sql
```

### 7. Run SQL Queries

Open the `queries` folder and execute the SQL files individually in numerical order.

**Note:** Use a database engine and SQL syntax compatible with your scripts. Check the database connection before executing the queries.

---

## 🧠 Learning Outcomes

Through this project, I gained practical experience in:

- Relational database design.
- Database creation and table management.
- Primary and foreign key constraints.
- CRUD operations.
- SQL joins and relationships.
- Aggregate functions.
- GROUP BY and HAVING.
- Subqueries.
- Date and string functions.
- Window functions.
- Conditional expressions.
- Writing structured SQL queries.

---

## 🔮 Future Improvements

Some improvements I would like to explore:

- Develop a React-based university management dashboard.
- Add student registration and authentication.
- Build an interactive course enrollment interface.
- Integrate a backend using Node.js and Express.
- Add department-wise analytics and reporting.
- Create interactive data visualization dashboards.

---

## 👨‍💻 Developer Profile

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=F75C7E&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Pal+Anghan;BCA+Graduate;Aspiring+Software+Developer;SQL+%7C+Python+%7C+MERN+Stack" alt="Developer Introduction" />

<br/>

**Pal Anghan**

BCA Graduate | Aspiring Software Developer | SQL & Full Stack Enthusiast

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-PalAnghan-181717?style=for-the-badge&logo=github)](https://github.com/PalAnghan)

[![Repository](https://img.shields.io/badge/Project-SQL--Final--Project-blue?style=for-the-badge&logo=github)](https://github.com/PalAnghan/SQL-Final-Project)

</div>

---

## ⭐ Support

If you find this project useful or interesting, please consider giving this repository a ⭐.

Your support motivates me to keep learning and building new projects!

<div align="center">

### 💻 Keep Learning. Keep Building. Keep Growing.

**Built with SQL, curiosity, and a passion for technology.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%" />

</div>
