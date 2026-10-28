# Hospital Management Database – SQL Project

## Project Scenario

A hospital provides healthcare services to patients through different medical departments and doctors. The hospital manages patient registrations, doctor information, appointments, treatments, and billing activities.

The hospital wants to develop a **Hospital Management Database** using MySQL to store and manage its daily operations in a structured way.

The database will help hospital management analyze patient information, appointment activity, doctor performance, treatment costs, billing details, and payment status using SQL queries.

## 1. Database Tables

### Patients

Stores patient details such as patient name, email, age, gender, city, registration date, and patient status.

### Departments

Stores department names and locations. Each department can have multiple doctors.

### Doctors

Stores doctor names, specializations, department IDs, experience, and consultation fees.

### Appointments

Stores patient appointments, doctor details, appointment dates, times, reasons, and status.

**Appointments may have different statuses, such as:**

- **Completed**
- **Cancelled**
- **Scheduled**

Appointment records help the hospital monitor patient visits, identify cancellation patterns, and understand doctor and department workload.

### Treatments

Stores treatment details, appointment IDs, treatment types, descriptions, costs, and dates.

### Billing

Stores patient and appointment IDs, bill dates, treatment amounts, consultation amounts, total amounts, payment methods, and payment status.

---

# SQL Business Analysis Questions

## Section 1: Basic Database Queries

1. Display all records from the hospital's database tables.
2. Count the total number of records in each database table.
3. Display the unique cities from which patients are registered.
4. Display patients in ascending order of their names.
5. Display patients from oldest to youngest.

## Section 2: Patient Analysis

6. Find patients whose status is Active and whose city is Mumbai.
7. Find patients whose age is between 30 and 50 years.
8. Find patients whose names begin with the letter A.
9. Identify patients whose email addresses are missing.
10. Use a CASE statement to classify patients into Young, Adult, and Senior age groups, and count patients in each group.

## Section 3: Appointment Analysis

11. Count appointments according to appointment status.
12. Display appointment details along with patient names and doctor names using JOIN.
13. Find appointments within a specified date range.
14. Calculate the percentage of cancelled appointments.
15. Find patients who have booked more than one appointment using GROUP BY and HAVING.

## Section 4: Doctor and Department Analysis

16. Display doctors along with their department names using JOIN.
17. Count the number of doctors working in each department.
18. Calculate the total number of appointments handled by each doctor.
19. Find doctors who have not received any appointments using LEFT JOIN.
20. Find the doctor with the highest number of completed appointments using a subquery.

## Section 5: Treatment Analysis

21. Display treatment details along with patient and doctor names using JOIN.
22. Calculate the total and average treatment cost.
23. Calculate the number of treatments and total treatment cost for each treatment type.
24. Find treatments costing more than ₹1,500.
25. Find the most expensive treatment record using a subquery.

## Section 6: Billing and Payment Analysis

26. Display billing records along with patient names and appointment details using JOIN.
27. Calculate the total billed amount, total paid amount, and total pending amount using aggregate functions and CASE statements.
28. Count bills and calculate total billed amounts according to payment status.
29. Find pending bills along with patient names and appointment IDs.
30. Create a SQL view containing billing details with patient, doctor, and department information, then use the view to summarize billing amounts by department.

---

# Project Objectives

- Store hospital information in a structured relational database.
- Retrieve and filter patient, doctor, appointment, treatment, and billing records.
- Analyze patient demographics and appointment activity.
- Understand doctor workload and department performance.
- Calculate treatment costs and billing totals.
- Analyze paid and pending payments.
- Practice SQL concepts including SELECT, WHERE, ORDER BY, GROUP BY, HAVING, JOIN, LEFT JOIN, aggregate functions, subqueries, CASE statements, and views.

# Project Conclusion

The Hospital Management Database SQL project demonstrates how MySQL can be used to store, retrieve, and analyze hospital information. The project covers patient analysis, appointment monitoring, doctor and department performance, treatment costs, and billing activities. It applies important SQL concepts, including filtering, sorting, joins, aggregate functions, grouping, subqueries, CASE statements, and views. Overall, this project provides practical experience in database management and develops SQL skills useful for data analysis.
