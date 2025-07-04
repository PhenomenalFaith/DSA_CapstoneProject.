# DSA_Palmora Group HR Data Analysis.
### Table of Contents.
- [Introduction.](#Introduction.)
- [Key Metrics.](#Key-Metrics.)
- [Tools Used.](#Tools-Used.)
- [Data Cleaning.](#Data-Cleaning.)
- [Visual Representation.](#Visual-Representation.)
- [Insights.](Insights.)
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

### Visual Representation.


![HR data Capstone project_page-0001](https://github.com/user-attachments/assets/61b0c7fb-e6b8-47de-9f40-bc87bdaf34bc)



![HR data Capstone project_page-0002](https://github.com/user-attachments/assets/e269927d-fdb1-4782-98c9-1c28667db59a)


### Insights.
- The gender distribution in Palmora Manufacturing Company shows a slight difference between the two genders, 0.6 % disparity.
- Based on regions, Kaduna had the highest number of male staffs with a difference of 13 compared to the female staff there; Abuja had a higher female staff with a difference of 7 compared to the male staff while Lagos had equal number of both genders.
- The legal department had the highest number of male staff and the marketing department had the least number of male staffs. The department with the highest female staff was the engineering department, dominating the male staff; followed by Research and Development department also superseding the male staff. The department with the least female staff is the accounting department.
- The very good rating with the highest amount happens to be the female gender with 53 as opposed to the male, with 37.The very poor rating had the highest being male (31) while female had 23 although 37 females were not rated while 34 male were also not rated.
- Overall, the Salary structure shows a little disparity between the male and female that earns above $90000. The difference being 18. 12 more females than males earned less than $90000. 321 males earned less than $90000 and 155 men earned more than $90000. On the other hand, 137 females earned above $90000 while 333 females earned below $90000
- Across the three regions, Abuja had more females earning $80000 -$89999 followed by $40000-$49999, then $30000-$39999 with more men as compared to females earning above $90000. In Kaduna, more females earned within the range $90000-$100999. We can also see that 16 more males than females  earned $110,000 and above.
- In Lagos, 4 more females than men earned $110000 and above also 5 more females than males earned between the range $90000-$99999.
- With regards to the increment regulation adopted, we still have 654 employees being paid less than $90000
and 292 employees earning above $90000.



