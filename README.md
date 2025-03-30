# Real Time Visibilty test of Payment Date Validty on PQP Marketing Consult


The idea behind the RTV3 Project is to be able to track the accuracy and integrity of the data newly entered into the newly created columns by the managers and also ensure completeness. In one of the PCT meetings discussions were raised on the accuracy of the data entered into the newly introduced columns. Therefore, the need to be able to validate the integrity of these data into the database. The new columns are Payment Date
Payment Date 2nd and Payment Date 3rd were introduced into the project and also empty from the initial set of the whole project.
The RTV3 Project is designed  to ensure systematic checks and validation processes to ensure the reliability of data entered into the database. This initiative will help maintain data accuracy, improve financial forecasting, and support better decision-making across the organization.


# Methodologies Used

 •  Nine tables were merged to one  **Global Table**
 
 .  Data Cleaning & Validation: Checked for invalid start dates and inconsistencies.
 
 •	Filtering & Segmentation: Used DAX filtering to analyze valid vs. invalid entries by manager.
 
 •	Data Visualization: Applied conditional formatting (red for invalid, green for valid) for quick insights.
 
 •	Trend Analysis: Observed patterns in registration dates, manager performance, and course distribution.

 


# Data Sources Analyzed

- Registration Date: Includes dates of registration and assigned start dates.
 
- Validity Check Date: Determines whether a start date, payment date, payment date 2nd /3rd is valid or not.
 
- Course Product: Displays the distribution of courses users have registered for.
 
- Manager Allocation: Tracks performance by individual managers, users they have registered and activated. 

- Location-Based Data: identify the user’s location as at registration

- Start Date: Indicates when a user’s course access begins.

- Payment Date: This identifies when a User makes their first down full or part payment

- Payment Date 2nd: This data identifies when a User makes a second down part or balance payment.

- Payment Date 3rd: This identifies when a User makes the final balance payment.

# •	Data Validation Patterns

- A significant portion of the registration data had invalid start dates, which could indicate manual entry errors or inconsistencies in date selection.

- The  Date Validity _Check" column clearly distinguishes between valid and invalid entries, allowing for easy identification of discrepancies.

- Green-highlighted rows represent valid entries, while red-highlighted rows indicate invalid start dates, making it visually clear where errors exist

  **KPIs**: Start date validity, Payment date validity, Payment date 2nd validity, Payment date 3rd validity.

![Screenshot 2025-03-30 092223](https://github.com/user-attachments/assets/ad0e93ba-1506-4f7a-b631-ab9b24b02448)



Key Findings & Insights

- Date Validity: Most registrations have valid start and payment dates, payments date 2nd /3rd  but some entries are invalid and need correction.

- Manager Performance: Managers have varying numbers of valid and invalid registrations, which can be analyzed for performance evaluation.

- Course Preference: Data Analytics has more registrations compared to Cyber Security, suggesting a higher demand for this course.

- Regional Trends: Both Abuja and Lagos contribute to registrations, but further analysis is needed to determine location-specific patterns.

- Registration Trends: There is a steady inflow of registrations over time, with some peak periods.

**Projected & Actual Impacts**

# Operational Efficiency Gains
1.	Estimated 90% reduction in invalid registrations after implementing automated validation.
2.	.50% improvement in processing efficiency by reducing manual corrections.
3.	Streamlined workflow leading to faster data processing and reporting.
# Stakeholder Satisfaction & Performance Improvements
1.	Increased Manager Accountability: By tracking performance metrics, managers are more likely to adhere to correct data entry processes.
2.	Improved Decision-Making: Cleaner data enables better forecasting and resource allocation.
# Financial & Business Impact
1.	Reduced Revenue Loss: Fewer errors mean minimized administrative overhead and better accuracy in financial reporting.
2.	Enhanced Reporting & Compliance: More accurate data improves regulatory compliance and operational transparency.

# Conclusion
Standardizing data entry through controlled inputs, predefined formats, and validation rules 
ensures accuracy, consistency, and efficiency in the registration workflow. By eliminating manual 
errors and enforcing structured data handling, organizations can improve decision-making, 
reduce processing delays, and enhance overall operational performance.


<img width="602" alt="image" src="https://github.com/user-attachments/assets/4641b21c-a032-4d48-9b48-429a772162b7" />




  












