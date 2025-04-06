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

  **KPIs**: Start date validity, Valid Start Date, Valid Payment Date, Valid Payment Date 2nd , Valid Payment Date 3rd, Date Validity Percentage 

<img width="145" alt="image" src="https://github.com/user-attachments/assets/6dda35f6-3c45-4001-9a6d-f6b60a172384" />




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

<img width="689" alt="image" src="https://github.com/user-attachments/assets/4041bc7a-f087-47bd-944f-e2144cf2a6bd" />
**Start Date Validity test Dashboard**

<img width="692" alt="image" src="https://github.com/user-attachments/assets/76a8be56-ab11-435f-9e4e-078297995083" />
**Payment Date Validity test Dashboard.**

<img width="692" alt="image" src="https://github.com/user-attachments/assets/147f9582-62da-4dc6-b90f-d0c0763eebcd" />
**Payment Date 2nd Validity test Dashboard**

<img width="689" alt="image" src="https://github.com/user-attachments/assets/53540d65-55fc-4513-b245-d6fd423398b8" />
**Payment Date 3rd Validity test Dashboard.**


  












