# TASK 2: Data Insertion & NULL Handling (MySQL)

**Done by:** Alefiya Joharbhai Managori  
**Goal:** Practice `INSERT`, `NULL`, `UPDATE`, and `DELETE` operations across a multi-table e-commerce schema.

---

## 🗂 Tables Involved
- User, Address, Product_Category, Product  
- Cart, Orders, Orders_Contains_Product  
- Payment, Tracking_Details

---

## ✅ Sample SQL Operations

### 🔹 Insert Data
```sql
INSERT INTO User VALUES (1, 'Aaliya', 'aaliya@gmail.com');
INSERT INTO Product VALUES (1, 'SmartPhone', 19999, '5G phone', 1);
```sql

### 🔹 Handle Null
```sql
INSERT INTO User (user_id, u_name, email) VALUES (2, 'Neha', NULL);
INSERT INTO Payment (pay_id, methods, amount, user_id) VALUES (1002, NULL, 1500, 2);
```sql

### 🔹 Update and Delete Data
```sql
UPDATE User SET u_name = 'Rahul Sharma' WHERE user_id = 2;
DELETE FROM User WHERE user_id = 3;
```sql

## 🧪 Output Checked With:
```sql
SELECT * FROM User;
SELECT * FROM Product;
```sql

## 📌 Summary
Inserted records into all tables

Used NULL to simulate missing data

Updated and deleted rows with conditions



