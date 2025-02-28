# File Title: E-Commerce_Business_Analysis

This was an independent project designed to showcase what I have learned in Business Analytics. The purpose was to analyze the companies' raw transaction logs and turn the event logs into business metrics.

<img src="https://github.com/robinsonmorgantaylor/Data_Projects_TripleTen/blob/main/Images/E-commerce%20Company.JPG">

Google Speadsheet can be found Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/111JNT17lCph2WHiEuLnt8sw5HPZGxxctehhumwqEi3o/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [E-commerce Company Project Requirements.txt](https://github.com/robinsonmorgantaylor/Data_Projects_TripleTen/blob/main/E-commerce%20Company/E-commerce%20Company%20Project%20Requirements.txt) | A simple .txt file with the project requirements as provided by TripleTen. |
| 2 | [E-commerce_Company_Project.pdf](https://github.com/robinsonmorgantaylor/Data_Projects_TripleTen/blob/main/E-commerce%20Company/E-commerce_Company_Project.pdf) | The completed project in a pdf file. |
| 3 | [E-commerce_Company_Project_Purchase_Activity.pdf](https://github.com/robinsonmorgantaylor/Data_Projects_TripleTen/blob/main/E-commerce%20Company/E-commerce_Company_Project_Purchase_Activity.pdf) | The purchase activity data provided by TripleTen. |
| 4 | [E-commerce_Company_Project_Raw_User_Activity.pdf](https://github.com/robinsonmorgantaylor/Data_Projects_TripleTen/blob/main/E-commerce%20Company/E-commerce_Company_Project_Raw_User_Activity.pdf) | The raw user activity data provided by TripleTen. |
| 5 | [E-commerce_Company_Review_Feedback.jpg](https://github.com/robinsonmorgantaylor/Data_Projects_TripleTen/blob/main/E-commerce%20Company/E-commerce_Company_Review_Feedback.JPG) | This is the feedback left by my project reviewer. |
| 6 | README.md | This current page with all relevant information about the project, just past the Table of contents. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| [Description](https://github.com/robinsonmorgantaylor/Data_projects_TripleTen/tree/main/E-commerce%20Company#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/robinsonmorgantaylor/Data_projects_TripleTen/tree/main/E-commerce%20Company#process) | A general outline of how this project formed from start to finish. |
| [Data](https://github.com/robinsonmorgantaylor/Data_projects_TripleTen/tree/main/E-commerce%20Company#data) | Describes the source of data, including files, tables, and fields. |
| [Assumptions](https://github.com/robinsonmorgantaylor/Data_projects_TripleTen/tree/main/E-commerce%20Company#assumptions) | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| [Findings](https://github.com/robinsonmorgantaylor/Data_projects_TripleTen/tree/main/E-commerce%20Company#findings) | Insights learned from the data analysis. |
| [Recommendations](https://github.com/robinsonmorgantaylor/Data_projects_TripleTen/tree/main/E-commerce%20Company#recommendations) | Recommended direction for the stakeholders based on the final analysis. |

#### Description:
- Worksheet with 8 sheets. 
- Includes operational tabs, raw data, processed data, data analysis, and pivot tables.

#### Process:
I first explored, filtered, and cleaned the data.
Then I created and built a conversion funnel.
I prepared data for cohort analysis.
Calculated retention rates.
Lastly, I finalized the formatting and documentation for the client's readability.

#### Data
The data was one Google spreadsheet file provided by TripleTen. Raw Data Google Spreadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1qWRY5svKGkJRyYNv7K4XvEGm9FpcoJhH5G0p4Qbq0V0/edit?usp=sharing' target=_blank><u>here</u>.</a>
- `'Business Analyst Project.csv'`: raw transaction logs
    - `'raw_user_activity'`: Each row represents an activity, or event, by a user on the company’s website
        - `'user_id'`: unique customer IDs
        - `'event_type'`: the type of activity by the user
        - `'category_code'`: category of the product being viewed or purchased
        - `'brand'`: the company that makes the product
        - `'price'`: price of the product, in USD
        - `'event_date'`: date of the user activity, in YYYY-MM-DD format
    - `'Table of Contents'`: Preformated yet empty table of contents sheet
    - `'Executive Summary`: Preformated yet empty executive summary sheet

#### Assumptions:
- The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data format (columns, data types) is correct and consistent.

#### Findings:
| Results | Synopsis |
| :-----------: | ----------- |
| Conversion Funnel | The total conversion rate from view to purchase was 10%. While the view-to-shopping cart conversion rate was 29% | 
| Retention Rates | Retention rates for the 2020-09 cohort group after the first month were only 13%; by the 4th month, it was down to 3% | 

### Recommendations:
- Address Shopping Cart Abandonment and Purchase Conversion. Future projects can focus on the best approach such as product page vs checkout process as a source of funnel deterioration.
- Enhance customer engagement and loyalty. Potential marketing campaigns could be personalized communications, loyalty programs, and looking into customer support.
- Gain customer feedback for a more targeted strategy.
- Continue data-driven insights to follow changes in the cohort analysis.
