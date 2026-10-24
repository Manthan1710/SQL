# Hospital Management Database – SQL & Power BI Project

## Project Scenario

A hospital provides healthcare services to patients through different medical departments and doctors. The hospital manages patient registrations, doctor information, appointments, treatments, and billing activities.

The hospital wants to develop a **Hospital Management Database** to store and manage its daily operations in a structured database. The system will help hospital management understand patient activity, doctor performance, department performance, treatment costs, billing information, and payment behaviour.

The project uses **MySQL for database management and SQL analysis**, along with **Power BI for data visualization and dashboard reporting**.

The database maintains information about patients, departments, doctors, appointments, treatments, and billing records.

### 1. Patients

The hospital stores personal information about every patient, such as their name, email, age, gender, city, registration date, and patient status.

A patient can book multiple appointments with different doctors. Patient information helps the hospital understand patient demographics, registration patterns, and healthcare service usage.

### 2. Departments

The hospital operates through different medical departments that provide specialized healthcare services.

For each department, the system stores details such as department name and location. Each department can have multiple doctors, and the department structure helps the hospital analyze doctor availability and department-level performance.

### 3. Doctors

The hospital employs doctors with different specializations and experience levels.

For each doctor, the system maintains information such as doctor name, specialization, department, experience, and consultation fee.

A doctor can handle multiple appointments. Doctor information helps the hospital analyze appointment workload, completed appointments, cancellation rates, and consultation fees.

### 4. Appointments

Patients book appointments with doctors for consultations, examinations, and follow-up visits.

The system records appointment information such as patient, doctor, appointment date, appointment time, appointment status, and reason.

Appointments may have different statuses, such as:

- Completed
- Cancelled
- Scheduled

Appointment records help the hospital monitor patient visits, identify cancellation patterns, and understand doctor and department workload.

### 5. Treatments

The hospital records treatments provided to patients during their appointments.

For each treatment, the system stores details such as appointment ID, treatment type, treatment description, treatment cost, and treatment date.

One appointment may have multiple treatment records. Treatment information helps the hospital analyze treatment costs, frequently recorded treatment types, and patient treatment activity.

### 6. Billing

The hospital maintains billing records for patient appointments and healthcare services.

For each bill, the system records details such as patient ID, appointment ID, bill date, treatment amount, consultation amount, total amount, payment method, and payment status.

Payment methods include options such as Cash, Card, and UPI. Bills may be marked as Paid or Pending.

Billing information helps the hospital monitor total billed amounts, collected payments, pending payments, monthly billing trends, and patient financial behaviour.

---

# Hospital Management SQL Project – Business Analysis Questions

## Basic Database & Record Analysis

1. The hospital wants to maintain a complete department directory. Display all department records.

2. Management wants to review the hospital's medical staff. Display all doctor records.

3. The hospital wants to maintain a complete patient directory. Display all registered patient records.

4. Display all appointment records to review the hospital's appointment schedule and activity.

5. Display all treatment records to review the treatments recorded by the hospital.

6. Display all billing records to review patient billing and payment information.

7. Count the total number of records in each database table to understand the amount of data maintained by the hospital.

## Patient & Basic Analysis

8. Identify the different cities from which patients are registered with the hospital.

9. Identify all patients whose current status is Active.

10. Find active patients who are registered in Mumbai.

11. Find patients registered in either Mumbai or Pune.

12. Identify patients registered in cities other than Mumbai.

13. Find patients whose age falls between 30 and 50 years for demographic analysis.

14. Identify patients belonging to Mumbai, Pune, Nashik, or Nagpur.

15. Find patients whose names begin with the letter A.

16. Identify patients whose email addresses are missing from the hospital records.

17. Identify patients who have a registered email address.

18. Display the five patients with the highest total billed amounts to identify patients with higher recorded billing activity.

19. Sort patients from oldest to youngest for age-based demographic analysis.

## Patient Profile & Segmentation

20. Identify active patients who are between 25 and 40 years old.

21. Find patients whose names contain the letter A for patient name analysis.

22. Display patients from Mumbai who are above 30 years of age.

23. Identify patients whose ages fall outside the range of 25 to 50 years.

24. Display patients whose city names start with the letter M.

25. Find patients whose email addresses belong to the Gmail domain.

26. Calculate the number of patients in each gender category.

27. Count patients according to their city and patient status to understand the patient distribution.

## Appointment Monitoring & Activity

28. Calculate the total number of appointments for each appointment status.

29. Display appointment details along with patient names and doctor names to understand which patients are visiting which doctors.

30. Identify appointments marked as Completed.

31. Display cancelled appointments along with patient names, doctor names, appointment dates, and appointment reasons.

32. Identify appointments scheduled within a specified date range for appointment activity analysis.

33. Find appointments whose reasons contain the word "pain".

34. Calculate the overall appointment cancellation percentage to understand the rate of cancelled appointments.

35. Identify patients who have both Completed and Cancelled appointments.

36. Identify patients who have booked more than one appointment with the hospital.

37. Find the most recent appointment date for each patient to understand their latest recorded hospital visit.

38. Calculate monthly appointment activity by grouping appointment records separately by year and month.

## Doctor & Department Performance Analysis

39. Display doctors along with their department names to understand the hospital's medical staff structure.

40. Identify doctors whose consultation fees are greater than ₹700.

41. Calculate the number of doctors working in each department.

42. Calculate the total number of appointments handled by each doctor to understand doctor workload.

43. Identify doctors who have handled more than three appointments.

44. Find the doctor with the highest number of Completed appointments.

45. Compare the number of Completed and Cancelled appointments for each doctor.

46. Identify doctors who have not received any appointments.

47. Calculate the number of doctors and appointments associated with each department.

48. Identify departments that have more than three appointments.

49. Find the department with the highest number of Completed appointments.

50. Identify departments sharing the same location for hospital department-location analysis.

## Treatment Analysis

51. Display treatment details along with patient names, doctor names, and department names to understand the treatment records.

52. Calculate the total and average treatment cost recorded by the hospital.

53. Calculate the number of treatments, total treatment cost, and average treatment cost for each treatment type.

54. Identify treatment records with costs greater than ₹1,500.

55. Find the most expensive treatment record in the hospital database.

56. Identify appointments that have multiple treatment records and calculate their combined treatment costs.

57. Calculate monthly treatment costs to understand changes in treatment activity over time.

58. Rank patients according to the sum of their recorded treatment costs to identify patients with higher recorded treatment expenses.

## Billing & Payment Analysis

59. Display all bills along with patient names and appointment details to review the hospital's billing records.

60. Calculate the total billed amount, total paid amount, and total pending amount.

61. Calculate the number of bills and total billed amount for each payment status.

62. Analyze the use of different payment methods by calculating the number of bills, total billed amount, and average bill amount for each method.

63. Identify bills with total amounts greater than ₹2,000.

64. Find the highest bill amount, including all bills tied at that amount.

65. Calculate the average bill amount recorded by the hospital.

66. Calculate monthly billing totals, including the number of bills, total billed amount, paid amount, and pending amount.

67. Identify patients who have a bill but do not have a treatment record for the corresponding appointment.

68. Identify Completed appointments that do not have a billing record.

69. Display pending bills along with patient names, appointment IDs, bill dates, and payment methods.

## Patient & Hospital Relationship Analysis

70. Display every patient along with their appointment, doctor, and department details, including patients who have not booked any appointments.

71. Identify hospital departments that do not currently have any doctors assigned to them.

72. Identify registered patients who have not booked any appointments with the hospital.

## Patient Service Usage & Financial Behaviour

73. Calculate the total number of bills and total amount paid by each patient to understand individual billing activity and payment behaviour.

74. Identify patients who have both Paid and Pending bills, including their respective bill counts and amounts.

75. Identify appointments that do not have a billing record, regardless of whether the appointment is Completed, Cancelled, or Scheduled.

76. Identify appointments that do not have any recorded treatment.

77. Identify patients who have used more than one payment method for their hospital bills.

78. Compare each patient's appointment activity with their total billed amount, paid amount, and pending amount.

## Case-Based Classification & Segmentation

79. Use CASE statements to classify patients into Young, Adult, and Senior categories based on age.

80. Calculate the number of patients in each age category to understand the hospital's demographic distribution.

81. Use CASE statements to classify treatment records into Low Cost, Medium Cost, and High Cost categories.

82. Calculate the number of treatments, total treatment cost, and average treatment cost for each treatment cost category.

83. Use CASE statements to classify bills into Low Value, Medium Value, and High Value categories based on their total amounts.

84. Calculate the number of bills, total billed amount, and average bill amount for each bill value category.

85. Use CASE statements to classify doctors into Early Career, Experienced, and Highly Experienced categories based on their years of experience.

## Advanced Doctor, Department & Revenue Analysis

86. Identify doctors whose consultation fees are greater than the average consultation fee of all doctors.

87. Analyze each doctor's total appointments, Completed appointments, Cancelled appointments, Scheduled appointments, and cancellation percentage.

88. Compare appointment activity, number of bills, total billed amount, paid amount, and pending amount across hospital departments.

89. Compare the consultation amount recorded on each bill with the listed consultation fee of the doctor handling the appointment.

## SQL Views for Reusable Analysis

90. Create a SQL view that summarizes each patient's profile, total appointments, appointment statuses, and latest appointment date.

91. Create a SQL view containing billing details along with the related patient, doctor, and department information.

92. Use the patient appointment summary view to analyze patient activity and identify patients with higher appointment counts.

93. Use the hospital billing detail view to review billing records with their associated patient, doctor, and department details.

94. Use the billing detail view to generate a department-level billing summary showing bill counts, total billed amounts, paid amounts, and pending amounts.

## Additional Data Quality Checks

95. Check whether any bills are attached to appointments marked Cancelled or Scheduled.

96. Identify treatment records associated with appointments that are not marked Completed.

97. Check whether the patient ID recorded in a bill matches the patient ID associated with its appointment.

---

# Project Conclusion

The Hospital Management Database SQL project provides a structured way to manage and analyze hospital information, including patients, departments, doctors, appointments, treatments, and billing records.

The SQL analysis helps hospital management understand patient demographics, monitor appointment activity, evaluate doctor workload, compare department performance, analyze treatment costs, and track billing and payment behaviour.

Patient service usage and financial analysis help identify patients with multiple appointments, patients using different payment methods, and patients with pending bills. CASE-based classification supports age-based segmentation, treatment cost analysis, and bill value classification.

SQL views make frequently used analysis easier to reuse, while data quality checks help identify potential inconsistencies between appointments, treatments, and billing records.

By connecting the database to Power BI, the project can be extended into interactive dashboards for monitoring hospital KPIs, appointment trends, department performance, treatment expenses, and financial activity.

Overall, this project demonstrates how SQL and Power BI can transform hospital data into meaningful business insights and support better operational and financial decision-making.

---

# SQL & Power BI Project Workflow

## 🏥 Hospital Management Database Project

```text
HOSPITAL MANAGEMENT DATABASE
             |
             v
        SQL DATABASE
             |
             +-- Departments
             +-- Doctors
             +-- Patients
             +-- Appointments
             +-- Treatments
             +-- Billing
             |
             v
        SQL ANALYSIS
             |
             +-- SELECT
             +-- WHERE
             +-- GROUP BY
             +-- HAVING
             +-- JOIN
             +-- SUBQUERIES
             +-- CASE STATEMENTS
             +-- AGGREGATE FUNCTIONS
             +-- SQL VIEWS
             +-- DATA QUALITY CHECKS
             |
             v
           POWER BI
             |
             +-- Data Connection
             +-- Data Cleaning
             +-- Data Modeling
             +-- Relationships
             +-- DAX Measures
             +-- KPI Cards
             +-- Charts & Graphs
             +-- Interactive Dashboards
```

## Technologies Used

- **Database:** MySQL
- **Data Analysis:** SQL
- **Data Visualization:** Microsoft Power BI
- **Project Documentation:** GitHub README

## Project Objectives

- Maintain hospital data in a structured relational database.
- Analyze patient demographics and appointment activity.
- Evaluate doctor workload and department performance.
- Analyze treatment costs and billing information.
- Monitor paid and pending payments.
- Identify potential data quality issues.
- Present meaningful hospital insights through Power BI dashboards.

## Future Scope

- Add more patient and appointment records for broader analysis.
- Create interactive Power BI dashboards for hospital KPIs.
- Analyze appointment trends and department-wise service usage.
- Develop more detailed financial reports.
- Extend the database with additional hospital modules if required.
