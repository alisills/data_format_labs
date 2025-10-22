# data_format_labs
This is a collection of labs to help with learning JSON, XML, and CSV.

Create Json and Convert them to Xml for each lab 
 
 
Lab 1. Exploring Data Types vs Data Formats using JSON

You are given the following mixed dataset: 

EmployeeID: 101,   number

EmployeeName: "Sathwik",   string

IsActive: true,   boolean

JoiningDate: 11-SEP-2025,   null

Salary: 50,00 INR null

1. Identify data types of each value. 

2. Convert the above dataset into a valid JSON format. 

{
    "Employee ID": 101,
    "EmployeeName": "Sathwick",
    "IsActive": true,
    "JoiningDate": "11-SEP-2025",
    "Salary": "100,000 USD",
}

3. Explain why JSON is considered a data format rather than a data type. 

JSON is considered a data format rather than a data type due to it defining and controling data types. 

 4. Create a nested JSON version by adding "Address" (with "City", "State", "PinCode") inside the JSON.  

 {
    "Employee ID": 101,
    "EmployeeName": "Sathwick",
    "IsActive": true,
    "JoiningDate": "11-SEP-2025",
    "Salary": "100,000 USD",

    "Address": "PO Box 75562",
    "City": "North Chesterfield",
    "State": "Virginia",
    "Zip Code": 23236
}

5. Point out one invalid JSON representation for this dataset and correct it. 

Both the date and salary was missing quotation marks which would make them a string. 

6. Justify why JSON is widely used in real-world applications for such data. 

 JSON is widely used in real-world applications for such data because of its readibility, lightweight, efficient and simplicity. 

 

 

 

 

 

Lab 2. Valid vs Invalid JSON with Nested Structures

Consider the following attempt to create a student record in JSON: 

{ 

  "StudentID": 2001, 

  "Name": 'Ravi Kumar', 

  "Subjects": ["Maths", "Science", "English",], 

  "Grades": {"Maths": 90, "Science": 85, "English": 92,} 

} 

  

1. Identify at least 3 reasons why this JSON is invalid. 

2. Correct the JSON into a valid structure. 

3. List the data types supported in JSON present in this dataset. 

4. Add a nested JSON for "Address" including "Street", "City", "Zip". 

5. Explain how data types differ from data formats in this context. 

6. Discuss one real-world use case where student data like this is shared using JSON and why JSON is advantageous. 

 

 

 

 

 

 

 

Lab 3. Building Complex Nested JSON for Real-World APIs

Imagine you are building a flight booking API. The booking data must include: 

Passenger details (Name, Age, IsForeignNational). 

Flight details (FlightNo, Departure, Arrival). 

Ticket details (PNR, Price, Currency). 

1. Design a nested JSON structure containing all the above data. 

2. Explain which data types are used for each field. 

3. Convert this into two different data formats (XML and CSV). 

4. Show one invalid JSON version of your answer and explain why it fails. 

5. Compare data types vs data formats in the context of your solution. 

6. Explain the advantages of JSON over XML in airline booking systems. 

Lab 4. Deep Dive into JSON in the Real World

You are given a real-world dataset representing an online product order: 

OrderID: 50045,   

Customer: "Anil Kumar",   

Products: [ {Name: "Laptop", Price: 75000}, {Name: "Mouse", Price: 1200} ],   

PaymentStatus: "Success" 

1. Create a valid nested JSON for this dataset. 

2. Identify JSON-supported data types used here. 

  

3. Show one invalid JSON version (with missing quotes or extra commas). 

4. Discuss why JSON is a data format and not a data type. 

5. Compare JSON vs another data format (XML or YAML) for this use case. 

6. Explain the real-world advantage of using JSON for e-commerce APIs. 

 

Lab 5. Data Type & Format Transformation Challenge

You are tasked with converting hospital patient data: 

PatientID: 9001,   

Name: "Rahul",   

Age: 29,   

IsInsured: true,   

Allergies: ["Peanuts", "Dust"] 

  

1. Identify data types for each attribute. 

2. Represent the dataset in valid JSON format. 

3. Create a nested JSON by adding "MedicalHistory" (PastIllness, CurrentMedication). 

4. Show one invalid JSON version and explain the mistake. 

5. Compare JSON with CSV for storing this data. 

6. Highlight why JSON is advantageous in healthcare data exchange. 

 

 

Lab 6. Advanced Comparison: JSON vs Other Data Formats

Suppose you are developing a music streaming app. A sample track record is 

TrackID: 301,   

Title: "Shape of You",   

Artist: "Ed Sheeran",   

Duration: 4.24,   

AvailableOn: ["Android", "iOS", "Web"] 

  

1. Convert this into valid JSON. 

2. Add a nested JSON for "Album" containing "AlbumName", "ReleaseYear". 

3. Identify all JSON-supported data types in your dataset. 

4. Show an invalid JSON version and explain why it’s wrong. 

5. Convert the same data into XML format and compare JSON vs XML. 

6. Explain how real-world apps like Spotify or YouTube Music benefit from JSON. 

 



 

Create Xml and Convert them to Json for each lab 
 
Lab 1: Library Management System

Objective: Work with root attributes and nested child elements. 

What is the location and established year of the library? (root-level attributes) 

List all book titles and their categories. 

Write the currency attribute to include both USD and INR. 

  

Lab 2: Student Information System

Objective: Model a student record with multiple subjects. 

Which semester and university is this data for? (root attributes) 

Show all student names and their program of study. 

A student atleast with with 3 subjects, making sure to use rollNo, program, and age attributes. 

For students list all subject codes and grades. 

  

  

Lab 3: Online Store Catalog

Objective: Represent a shopping catalog with attributes and stock details. 

What is the store name, country, and established year? 

List all products with their category and warranty. 

Find the stock availability of the item. 

  

  

  

Lab 4: Airline Reservation System

Objective: Model flight bookings with passenger details. 

What is the hub and fleet size of the airline? 

List all passenger names, ticket types, and seat numbers. 

The arrival time and departure time of flight should be there. 

  

 

 

 

Lab 5: Music Playlist

Objective: Represent music playlist with attributes like duration. 

What is the playlist name, creator, and total number of songs? 

List all song titles, genres, duration and artists’ countries. 

  

  

Lab 6: Employee Payroll System

Objective: Model employee payroll data with salary breakdown. 

What is the payroll company name, month, and year? 

List all employees with their designation and department. 



Create Csv and Convert them to Xml and Json for each lab. 
 
Lab 1 – Online Electronics Store

Objective: Create CSV files for an online electronics shop. 

• CSV Files: 
1. Vendors.csv → vendorId, name, city 
2. Products.csv → productId, name, category (Laptop, Mobile, TV), vendorId, price 
3. Customers.csv → custId, name, email, phone 
4. SalesOrders.csv → orderId, custId, productId, qty, totalAmount 
 

Lab 2 – Education System

Objective: Model CSV files for a university library. 

• CSV Files: 
1. Libraries.csv → libraryId, name, location 
2. Books.csv → bookId, title, author, libraryId 
3. Students.csv → studentId, name, department, year 
4. BorrowRecords.csv → borrowId, studentId, bookId, borrowDate, returnDate 
 

Lab 3 – Hospital Laboratory Reports

Objective: Create CSV files for a hospital lab system. 

• CSV Files: 
1. LabTechnicians.csv → techId, name, specialization 
2. Patients.csv → patientId, name, age, gender 
3. Tests.csv → testId, name, type (Blood, XRay, MRI, ECG) 
4. LabReports.csv → reportId, patientId, testId, techId, resultSummary, reportDate 
 

Lab 4 – Bank Loan Management

Objective: Build CSV files for a bank’s loan system. 

• CSV Files: 
1. Customers.csv → customerId, name, dob, contact 
2. LoanAccounts.csv → loanId, customerId, type (Home, Car, Education), principalAmount, interestRate 
3. Repayments.csv → repaymentId, loanId, date, amountPaid 
4. Guarantors.csv → guarantorId, name, loanId, relationship 
 

Lab 5 – Retail Inventory Management

Objective: Create CSV files for a retail inventory system. 

• CSV Files: 
1. Suppliers.csv → supplierId, name, location 
2. Products.csv → productId, supplierId, name, category 
3. Stores.csv → storeId, name, city 
4. StockLevels.csv → stockId, storeId, productId, availableQty, lastUpdated 
 

Lab 6 – Airline Reservation System

Objective: Design CSV files for airline reservations. 

• CSV Files: 
1. Airports.csv → airportId, name, city, country 
 

2. Flights.csv → flightId, airline, sourceAirport, destAirport, departureTime 
3. Passengers.csv → passengerId, name, age, passportNo 
4. Bookings.csv → bookingId, passengerId, flightId, seatNo, ticketPrice 
  

 