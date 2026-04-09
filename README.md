# banking_transactions_systems
bfsi 1st repository
## 🗂️ Database Structure

The project consists of two main tables:

### 1. Customers Table
Stores customer details:
- Customer ID (Primary Key)
- Name
- Email
- City
- Account Type (Savings/Current)
- Account Balance

### 2. Transactions Table
Stores transaction records:
- Transaction ID (Primary Key)
- Customer ID (Foreign Key)
- Amount
- Transaction Type (Credit/Debit)
- Transaction Mode (UPI, ATM, NEFT, IMPS)
- Transaction Date

---

## ⚙️ Features & SQL Concepts Used

- ✅ Table creation with constraints (Primary Key, Foreign Key)
- ✅ Insert multiple records
- ✅ Filtering using `WHERE`
- ✅ Sorting using `ORDER BY`
- ✅ Aggregate functions (`SUM`, `AVG`)
- ✅ `GROUP BY` and `HAVING`
- ✅ Subqueries
- ✅ Window functions:
  - `SUM() OVER (PARTITION BY...)` (Running Total)
  - `DENSE_RANK()`

---

## 📊 Sample Queries Included

- Customers with balance greater than 10,000  
- Transactions sorted by latest date  
- Unique transaction modes  
- Top 5 highest transactions  
- Customers whose name starts with 'A'  
- Total transaction amount per customer  
- Running total of transactions  
- Ranking customers by balance  
- Customers with above-average transaction amount  

---

## 🛠️ How to Run This Project

1. Install MySQL (or use XAMPP/phpMyAdmin)  
2. Open MySQL console or phpMyAdmin  
3. Copy and paste the SQL script  
4. Run the script to:
   - Create database  
   - Create tables  
   - Insert data  
   - Execute queries  

---

## 🧠 Learning Outcomes

- Understanding relational database design  
- Writing optimized SQL queries  
- Using advanced SQL features like window functions  
- Working with real-world banking-like data  

---

## 📁 File Structure
bank-system/
│── bank_system.sql # Main SQL script
│── README.md # Project documentation

---

## 🚀 Future Improvements

- Add stored procedures  
- Implement triggers  
- Build a frontend using PHP/HTML  
- Connect with a real-time application  
