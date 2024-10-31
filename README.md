TASKS:
Creating Collections:
  1.Create a collection named Employees with fields: EmployeeID, FirstName, LastName, DateOfBirth, and Department.
  2.Create a collection named Orders with fields: OrderID, OrderDate, CustomerID, and Amount.
Inserting Data into Collections:
  3.Insert a new employee into the Employees collection with the following data: EmployeeID: 1, FirstName: 'Alice', LastName: 'Johnson', DateOfBirth: '1990-01-15', Department: 'HR'.
  4.Insert multiple records into the Orders collection with different OrderDates, CustomerIDs, and Amounts.
Selecting Data from Collections:
  5.Select all documents from the Employees collection.
  6.Select all documents from the Orders collection.
  7.Select only the FirstName and LastName from the Employees collection.
  8.Select the OrderID and Amount from the Orders collection.
Updating Data in a Collection:
  9.Update the Department of the employee with EmployeeID 1 to 'Finance'.
  10.Update the Amount in the Orders collection where OrderID is 2 to 500.00.
Deleting Data from a Collection:
  11.Delete the employee from the Employees collection where EmployeeID is 1.
  12.Delete all orders from the Orders collection where the Amount is less than 100.
Filtering Data with WHERE Clause:
  13.Select all employees who work in the 'HR' department.
  14.Select all orders with an Amount greater than 300.
Using AND / OR in Queries:
  15.Select employees who work in the 'HR' department and were born after '1990-01-01'.
  16.Select orders with an Amount greater than 300 and OrderDate before '2023-01-01'.
  17.Select employees who work in either the 'HR' or 'Finance' department.
  18.Select orders with an Amount less than 100 or placed after '2023-01-01'.
Sorting Results with ORDER BY:
  19.Select all employees and order the results by LastName in ascending order.
  20.Select all orders and order the results by Amount in descending order.
Using Aggregate Functions:
  21.Count the number of employees in the Employees collection.
  22.Count the number of orders placed in the Orders collection.
  23.Find the average Amount of all orders in the Orders collection.
  24.Calculate the average age of employees (assuming there’s a function to calculate age from DateOfBirth).
Grouping Data with GROUP BY:
  25.Count the number of employees in each Department.
  26.Calculate the total Amount of orders for each CustomerID.
Using HAVING Clause:
  27.Find all departments that have more than 5 employees.
  28.Find all CustomerIDs with total order Amount greater than 1000.
Joining Collections:
  29.Inner Join: Join Employees and Orders on CustomerID (assuming employees are customers) and select FirstName, LastName, and Amount.
  30.Left Join: Perform a left join between Employees and Orders, returning all employees and their corresponding Order Amount if available.


PROJECT:
 University Database System
     Collections: Students, Courses, Enrollments, Instructors, Departments
     Tasks:
         =>Create collections for students, courses, and enrollments.
         =>Insert students with details like StudentID, FirstName, LastName, and Major.
         =>Query to select all students enrolled in a specific course.
         =>Update a student's major or department.
         =>Delete records of students who have graduated.
         =>Filter students based on the course they are enrolled in.
         =>Use AND/OR to find students enrolled in multiple courses.
         =>Sort students by last name in alphabetical order.
         =>Use aggregate functions to count the total number of students.
         =>Group students by major and calculate the average enrollment in each major.
