# API Testing with JMeter — CRUD Book API

**Objective:**  
Perform CRUD API testing using Apache JMeter with CSV-based data-driven testing.

**Endpoints:**
- GET `/books`
- POST `/books`
- PUT `/books/{id}`
- POST `/books/authToken`
- DELETE `/books/{id}`


**Features:**
- Automated Create, Read, Update, Delete workflows  
- CSV data-driven POST requests  
- Authorization-based DELETE  
- Assertions for validation  
- Thread groups for concurrent execution  

**Files:**
- BookAPI_TestPlan.jmx  
- books_data.csv  
- post_request.json  
- README.md

**How to Run the Test**

1. Open **Apache JMeter**
2. Load `BookAPI_TestPlan.jmx`
3. Update your **API base URL** and **Authorization token**
4. Click ▶️ **Start** to execute
5. View results in **Summary Report** or **View Results Tree**

**Expected Output:**
- Books added via CSV  
- Data retrieved via GET  
- Updated via PUT  
- Deleted via DELETE  

**Author:** Mehwish Khan  
**Role:** QA Intern  
**Date:** October 2025
