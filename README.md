# Capgemini SQL Practice Labs 🚀

A comprehensive collection of SQL queries, data manipulation tasks, and practical database assignments based on real-world enterprise scenarios from **The Kiran Academy**.

---

## 🗄️ Database & Schema Overview

- **Database Name:** `capgemini`
- **Table Name:** `employee`

### Table Structure & Initial Dataset

| id | name | profile | email | salary | age | experience |
|----|------|---------|-------|--------|-----|------------|
| 1 | rani | dev | rani@gmail.com | 11000 | 43 | 27 |
| 2 | raj | test | raj@gmail.com | 21000 | 33 | 17 |
| 3 | radha | test | radha@gmail.com | 26000 | 38 | 21 |
| 4 | raj | xdev | raj12@gmail.com | 51000 | 32 | 12 |
| 5 | john | dev | john@gmail.com | 51000 | 39 | 27 |

---

## 📋 Assignment Queries & Solutions

### 1. Retrieve employee names with salary > 20,000
SELECT name FROM employee WHERE salary > 20000;
2. Retrieve all information for employees with salary = 51,000
SQL
SELECT * FROM employee WHERE salary = 51000;
3. Retrieve name and experience for employees whose age > 35
SQL
SELECT name, experience FROM employee WHERE age > 35;
4. Retrieve all employees belonging to the 'dev' profile
SQL
SELECT * FROM employee WHERE profile = 'dev';
5. Retrieve employee names with the 'test' profile
SQL
SELECT name FROM employee WHERE profile = 'test';
6. Retrieve records of employees with salary >= 25,000
SQL
SELECT * FROM employee WHERE salary >= 25000;
7. Retrieve employee name and email for those not earning 51,000
SQL
SELECT name, email FROM employee WHERE salary != 51000;
8. Update employee salary by +10K for experience < 20 years
SQL
UPDATE employee SET salary = salary + 10000 WHERE experience < 20;
9. Remove employee record who has 21 years of experience
SQL
DELETE FROM employee WHERE experience = 21;
10. Decrease john's salary by 21K for cost-cutting
SQL
UPDATE employee SET salary = salary - 21000 WHERE name = 'john';
🚀 Getting Started
Clone the repository:

Bash
git clone [https://github.com/username/capgemini-sql-practice-labs.git](https://github.com/username/capgemini-sql-practice-labs.git)
Import the schema and execute queries in your MySQL / relational database management environment.

👤 Connect With Me
📄 License
This project is licensed under the MIT License.
