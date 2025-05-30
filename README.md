# 📊 Real-Time Visibility Analysis: Payment Date Validation for PQP Marketing Consult

- [Objective](#objective)
- [Tools Used](#tools-used)
- [Data Sources Analyzed](#data-sources-analyzed)
- [DAX Logic & Validations](#dax-logic--validations)
- [Data Validation Pattern](#data-validation-pattern)
- [Dashboard Highlights](#dashboard-highlights)
- [Key Findings & Insights](#key-findings--insights)
- [Projected & Actual Impacts](#projected--actual-impacts)
- [Conclusion](#conclusion)
- [Contact](#contact)

# Objective
The RTV3 Project focuses on enhancing the data accuracy and completeness of payment date entries newly added to the institutional database. During PCT meetings, issues were raised regarding incorrect and incomplete values in the new date fields—particularly Payment Date 2nd and Payment Date 3rd. This project introduces a real-time validation logic using Power BI to detect these issues and empower managers to take prompt action.
With systematic checks and dynamic dashboards, the solution helps maintain data integrity, improve forecasting, and support smarter decision-making.


# tools used
**Power Query Editor**
**Power BI**


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

# Dashboard Highlights

Below is a snapshot of the Power BI dashboard that tracks row-level validity:

<img width="663" alt="Power BI Dashboard " src="https://github.com/user-attachments/assets/65467226-917b-4944-8d71-4116c9e0ee17" />
**Start Date Validity test Dashboard**

<img width="654" alt="Power BI Dashboard 1" src="https://github.com/user-attachments/assets/f1bc27a5-28c7-4f7b-9842-453ed0702032" />
**Payment Date Validity test Dashboard.**

<img width="659" alt="Power BI Dashboard 2" src="https://github.com/user-attachments/assets/4392f626-0b03-4b32-a263-436f251c0885" />
**Payment Date 2nd Validity test Dashboard**

<img width="658" alt="Power BI Dashboard 3" src="https://github.com/user-attachments/assets/e7bd9e01-b513-4cb0-8b6f-fadebc20f834" />
**Payment Date 3rd Validity test Dashboard.**


## 🧮 DAX Logic & Validations

Key validation rules applied:

- ✅ Registration Date < Start Date  
- ✅ Start Date < Payment Date 2nd  
- ✅ Payment Date 2nd < Payment Date 3rd

Sample DAX formula to compute valid rows:

```DAX
Valid_Row_Count = 
CALCULATE(
    COUNTROWS('PQP_Data'),
    'PQP_Data'[Date_Validation_Status] = "Valid"
)

**Percentage of Valid Row Count

Valid_Row_Percentage = 
DIVIDE([Valid_Row_Count], [Total_Row_Count], 0)

## Data Validation Patterns

- A significant portion of the registration data had invalid start dates, which could indicate manual entry errors or inconsistencies in date selection.

- The  Date Validity _Check" column clearly distinguishes between valid and invalid entries, allowing for easy identification of discrepancies.

- Green-highlighted rows represent valid entries, while red-highlighted rows indicate invalid start dates, making it visually clear where errors exist


# Key Findings & Insights

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



## 📩 Contact

**Damissah Deborah**  
📧 [damissahdeborah@gmail.com](mailto:damissahdeborah@gmail.com)  


  












