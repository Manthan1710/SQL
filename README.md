Hospital Management Database – SQL Project
Project Scenario
A hospital provides healthcare services to patients through different medical departments and doctors. The hospital manages patient registrations, doctor information, appointments, treatments, and billing activities.
The hospital wants to develop a Hospital Management Database using MySQL to store and manage its daily operations in a structured way.
The database will help hospital management analyse patient information, appointment activity, doctor performance, treatment costs, billing details, and payment status using SQL queries.
1. Database Tables
Patients
Stores patient details such as patient name, email, age, gender, city, registration date, and status.
Departments
Stores department names and locations. Each department can have multiple doctors.
Doctors
Stores doctor names, specializations, department IDs, experience, and consultation fees.
Appointments
Stores patient appointments, doctor details, appointment dates, times, reasons, and status.
Appointments may have different statuses, such as:
•	Completed
•	Cancelled
•	Scheduled
Treatments
Stores treatment details, appointment IDs, treatment types, descriptions, costs, and dates.
Billing
Stores patient and appointment IDs, bill dates, treatment amounts, consultation amounts, total amounts, payment methods, and payment status.
________________________________________
Project Objectives
•	Store hospital information in a structured relational database.
•	Retrieve and filter patient, doctor, appointment, treatment, and billing records.
•	Analyse patient demographics and appointment activity.
•	Understand doctor workload and department performance.
•	Calculate treatment costs and billing totals.
•	Analyse paid and pending payments.
•	Practice SQL joins, aggregate functions, GROUP BY, HAVING, subqueries, CASE statements, and views.
•	Identify missing records and possible inconsistencies in hospital data.
________________________________________
SQL Business Analysis Questions
The following 50 questions cover basic SQL queries, filtering, sorting, aggregate functions, grouping, joins, subqueries, CASE statements, views, and data quality checks.
Section 1: Basic Database Queries
1.	Display all department records.
2.	Display all doctor records.
3.	Display all patient records.
4.	Display all appointment records.
5.	Display all treatment records.
6.	Display all billing records.
7.	Count the total number of records in each table.
Section 2: Patient Analysis
8.	Display the unique cities from which patients are registered.
9.	Find all active patients.
10.	Find active patients registered in Mumbai.
11.	Find patients registered in either Mumbai or Pune.
12.	Find patients whose age is between 30 and 50 years.
13.	Find patients whose names begin with the letter A.
14.	Find patients whose email addresses are missing.
15.	Sort patients from oldest to youngest.
16.	Count patients according to gender.
17.	Count patients according to city and status.
Section 3: Appointment Analysis
18.	Count appointments according to appointment status.
19.	Display appointment details along with patient names and doctor names.
20.	Find appointments marked as Completed.
21.	Display cancelled appointments with patient and doctor details.
22.	Find appointments within a specified date range.
23.	Find appointments whose reasons contain the word "pain".
24.	Calculate the percentage of cancelled appointments.
25.	Find patients who have booked more than one appointment.
26.	Find the latest appointment date for each patient.
27.	Calculate monthly appointment counts.
Section 4: Doctor and Department Analysis
28.	Display doctors along with their department names.
29.	Find doctors whose consultation fees are greater than ₹700.
30.	Count the number of doctors in each department.
31.	Calculate the total number of appointments handled by each doctor.
32.	Find doctors who have handled more than three appointments.
33.	Find doctors who have not received any appointments.
34.	Count appointments for each department.
35.	Find the department with the highest number of completed appointments.
Section 5: Treatment Analysis
36.	Display treatment details along with patient and doctor names.
37.	Calculate the total and average treatment cost.
38.	Calculate the number of treatments and total cost for each treatment type.
39.	Find treatments costing more than ₹1,500.
40.	Find the most expensive treatment record.
41.	Calculate monthly treatment costs.
Section 6: Billing and Payment Analysis
42.	Display billing records along with patient names and appointment details.
43.	Calculate the total billed amount, total paid amount, and total pending amount.
44.	Count bills and calculate billed amounts according to payment status.
45.	Analyse payment methods by counting bills for each method.
46.	Find bills with total amounts greater than ₹2,000.
47.	Calculate the average bill amount.
48.	Find pending bills along with patient names.
Section 7: SQL Concepts and Advanced Analysis
49.	Use a CASE statement to classify patients into Young, Adult, and Senior age groups, and count patients in each group.
50.	Create a SQL view containing billing details with patient, doctor, and department information, then use the view to summarize billing amounts by department.
________________________________________
Project Conclusion
The Hospital Management Database SQL project demonstrates how MySQL can be used to store, retrieve, and analyse hospital information.
The project covers patient analysis, appointment monitoring, doctor and department performance, treatment costs, and billing activities. It uses SQL concepts such as SELECT, WHERE, ORDER BY, GROUP BY, aggregate functions, joins, subqueries, CASE statements, and views.
This project provides practical experience in database management and helps develop the SQL skills required for data analysis.

