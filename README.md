# DSA_Palmora Group HR Data Analysis.
### Table of Contents.
- [Introduction.](#Introduction.)
- [Key Metrics.](#Key-Metrics.)
- [Tools Used.](#Tools-Used.)
- [Data Cleaning.](#Data-Cleaning.)
- [Visual Representation.](#Visual-Representation.)
- [Conclusion.](#Conclusion.)
- [Recommendation.](#Recommendation.)
- [Author.](#Author.)

### Introduction.
Palmora Group is a manufacturing company in Nigeria with branches in Lagos, Kaduna and Abuja. In recent times, they have been faced with the allegation of Gender inequality amongst their staff. This dataset is to reveal the gender distribution across the three regions using some conditions to see if the allegations are true and how to best advise the management moving forward to ensure continuity in business, scaling to higher altitudes and a good reputation before their stakeholders.

### Key Metrics.
- Gender distribution in the organisation
- Gender distribution based on ratings, regions, and departments.
- Compliance with the new regulation of minimum payment of $90,000 to employees.
- Pay Distribution in the range of $10,000 and the number of employees within the category.
- Bonus according to Ratings for the different departments.
- Total amount (bonus inclusive) paid to the employees based on the regions.


 ### Tools Used.
 - Microsoft Excel: For data cleaning.
 - Microsoft Power BI: For data cleaning and data visualisation.
 - Coolors: For selecting a colour palette.

### Data Cleaning.
 Two datasets were given: *the Palmora HR employee dataset and Bonus rating dataset*. The employee dataset consisted of six columns and one thousand and fifteen rows. The null values for the salary column (43 rows) and null values for the Department column (26 rows) indicating employees which were no longer with the firm were removed. After removal, the employees without gender( 40 rows) were given generic genders and the total rows left were 946 rows after the cleaning process.
 
 <img width="960" alt="Data cleaning (Salary removal) " src="https://github.com/user-attachments/assets/2cc2bba0-0cde-4e4e-be59-7fb43f6194c4" />

 <img width="960" alt="Data Cleaning Null Job role" src="https://github.com/user-attachments/assets/f84a6c22-9df5-41b6-91f3-a9daefdb6973" />

 <img width="908" alt="Data Cleaning  Emp data" src="https://github.com/user-attachments/assets/2f084143-f924-447d-89ec-19df9b9fa199" />

The bonus rating file was unpivoted and merged in Power BI using Rating and Department as the matching columns. Then, custom columns were used to calculate Bonus, Gross Salary, etc. A conditional column was used to separate the number of employees who were paid below $90000 and above $90000 to see how compliant Palmora is with the new regulation.




