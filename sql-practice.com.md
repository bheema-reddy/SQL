# SQL Problems 
Here is a breakdown of the SQL queries categorized by difficulty level that I have solved for covering all the basic concepts from 
<br/>
[Sql-practice.com](https://www.sql-practice.com/):


### **Easy**

1. Show first name, last name, and gender of patients whose gender is 'M'
2. Show first name and last name of patients who does not have allergies. (null)
3. Show first name of patients that start with the letter 'C'
4. Show first name and last name of patients that weight within the range of 100 to 120 (inclusive)
5. Update the patients table for the allergies column. If the patient's allergies is null then replace it with 'NKA'
6. Show first name and last name concatenated into one column to show their full name.
7. Show first name, last name, and the full province name of each patient.
8. Show how many patients have a birth_date with 2010 as the birth year.
9. Show the first_name, last_name, and height of the patient with the greatest height.
10. Show all columns for patients who have one of the following patient_ids: 1,45,534,879,1000
11. Show the total number of admissions
12. Show all the columns from admissions where the patient was admitted and discharged on the same day.
13. Show the patient id and the total number of admissions for patient_id 579.
14. Based on the cities that our patients live in, show unique cities that are in province_id 'NS'?
15. Write a query to find the first_name, last name, and birth date of patients who has height greater than 160 and weight greater than 70
16. Write a query to find list of patients first_name, last_name, and allergies where allergies are not null and are from the city of 'Hamilton'
17. Show the category_name and description from the categories table sorted by category_name.
18. Show all the contact_name, address, city of all customers which are not from 'Germany', 'Mexico', 'Spain'
19. Show order_date, shipped_date, customer_id, Freight of all orders placed on 2018 Feb 26
20. Show the employee_id, order_id, customer_id, required_date, shipped_date from all orders shipped later than the required date
21. Show all the even numbered Order_id from the orders table.
22. Show the city, company_name, contact_name of all customers from cities which contains the letter 'L' in the city name, sorted by contact_name
23. Show the company_name, contact_name, fax number of all customers that has a fax number. (not null)
24. Show the first_name, last_name, hire_date of the most recently hired employee.
25. Show the average unit price rounded to 2 decimal places, the total units in stock, total discontinued products from the products table.

### **Medium**

1. Show unique birth years from patients and order them by ascending.
2. Show unique first names from the patients table which only occurs once in the list.
3. Show patient_id and first_name from patients where their first_name start and ends with 's' and is at least 6 characters long.
4. Show patient_id, first_name, last_name from patients whose diagnosis is 'Dementia'.
5. Display every patient's first_name. Order the list by the length of each name and then alphabetically.
6. Show the total amount of male patients and the total amount of female patients in the patients table. Display the two results in the same row.
7. Show first and last name, allergies from patients which have allergies to either 'Penicillin' or 'Morphine'. Show results ordered ascending by allergies then by first_name then by last_name.
8. Show patient_id, diagnosis from admissions. Find patients admitted multiple times for the same diagnosis.
9. Show the city and the total number of patients in the city. Order from most to least patients and then by city name ascending.
10. Show first name, last name and role of every person that is either patient or doctor. The roles are either "Patient" or "Doctor".
11. Show all allergies ordered by popularity. Remove 'NKA' and NULL values from query.
12. Show all patient's first_name, last_name, and birth_date who were born in the 1970s decade. Sort the list starting from the earliest birth_date.
13. Display patient's full name with their last_name in all upper letters first, then first_name in all lower case letters, separated by a comma. Order the list by the first_name in descending order.
14. Show the province_id(s), sum of height; where the total sum of its patient's height is greater than or equal to 7,000.
15. Show the difference between the largest weight and smallest weight for patients with the last name 'Maroni'.
16. Show all of the days of the month (1-31) and how many admission_dates occurred on that day. Sort by the day with most admissions to least admissions.
17. Show all columns for patient_id 542's most recent admission_date.
18. Show patient_id, attending_doctor_id, and diagnosis for admissions that match one of the two criteria:
   - patient_id is an odd number and attending_doctor_id is either 1, 5, or 19.
   - attending_doctor_id contains a 2 and the length of patient_id is 3 characters.
19. Show first_name, last_name, and the total number of admissions attended for each doctor.
20. For each doctor, display their id, full name, and the first and last admission date they attended.
21. Display the total amount of patients for each province. Order by descending.
22. For every admission, display the patient's full name, their admission diagnosis, and their doctor's full name who diagnosed their problem.
23. Display the first name, last name, and number of duplicate patients based on their first name and last name.
24. Display patient's full name, height in the unit feet rounded to 1 decimal, weight in the unit pounds rounded to 0 decimals, birth_date, and gender non-abbreviated.
25. Show patient_id, first_name, last_name from patients whose does not have any records in the admissions table.
26. Show the ProductName, CompanyName, CategoryName from the products, suppliers, and categories table.
27. Show the category_name and the average product unit price for each category rounded to 2 decimal places.
28. Show the city, company_name, contact_name from the customers and suppliers table merged together. Create a column which contains 'customers' or 'suppliers' depending on the table it came from.

### **Hard**

1. Show all of the patients grouped into weight groups. Show the total amount of patients in each weight group. Order the list by the weight group descending.
2. Show patient_id, weight, height, isObese from the patients table. Display isObese as a boolean 0 or 1.
3. Show patient_id, first_name, last_name, and attending doctor's specialty. Show only the patients who have a diagnosis as 'Dementia' and the doctor's first name is 'Lisa'.
4. Show the patient_id and temp_password for patients given a temporary password after their first admission.
5. Calculate admission costs based on insurance status and show the total cost for each group.
6. Show the provinces that have more patients identified as 'M' than 'F'. Must only show full province_name.
7. Pull all columns for the patient who matches specific criteria based on name, gender, birth month, weight, patient_id, and city.
8. Show the percent of patients that have 'M' as their gender, rounded to the nearest hundredth number and in percent form.
9. Display the total amount of admissions on each day along with the change from the previous date.
10. Sort the province names in ascending order in such a way that the province 'Ontario' is always on top.
11. Show a breakdown for the total amount of admissions each doctor has started each year. Show the doctor_id, doctor_full_name, specialty, year, and total_admissions for that year.
12. Show the employee's first_name and last_name, a "Num_Orders" column with a count of the orders taken, and a "Shipped" column that displays "On Time" or "Late".
13. Show how much money the company lost due to giving discounts each year, order the years from most recent to least recent.
