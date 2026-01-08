
---

## Tables Description

| Table       | Description |
|------------|-------------|
| **Members** | Contains member details like name, contact, address, join date |
| **Books**   | Contains book details including title, author, genre, and copies |
| **Staff**   | Library staff information with positions and hire date |
| **Borrowing** | Tracks which member borrowed which book and status of return |

---

## Key SQL Queries

1. **Top 10 Most Borrowed Books** – Shows the most popular books in the library  
2. **Members With More Than 5 Late Returns** – Identifies members frequently returning books late  
3. **Current Books on Loan** – Lists all books currently borrowed and not yet returned  
4. **Most Borrowed Genres (Window Function)** – Ranks book genres by total borrowings  
5. **Top 10 Most Active Members** – Shows members who borrow the most books  

---

## How to Run

1. Place all CSV files in the `csv_files` folder  
2. Open **pgAdmin → Query Tool**  
3. Run `create_tables.sql` to create tables  
4. Run `insert_data.sql` to import CSV data  
5. Run `queries.sql` to execute all analytical queries  
6. (Optional) Export query results as CSV or screenshots for GitHub

---

## Technologies Used
- PostgreSQL  
- SQL Joins, Aggregation, and Window Functions  
- CSV Data Import  

---

## Author

**Muhammad Luqman**  
Data Analyst | SQL | Python | Power BI  

---

