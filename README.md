# Business Insights 360 - Power BI
- I worked on this project during my Codebasics Power BI Course, the Link to the course is [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)
- Link to [Portfolio Website](https://codebasics.io/portfolio/Amogh-Sawant)
- Link to [Live Dashboard](https://www.novypro.com/project/business-insights-360-power-bi-21)

## Problem Statement
AtliQ Hardware is a consumer goods electronics company having operations in various countries. It sells, computers and computer accessories through three mediums/channel
1. Retailer
2. Direct
3. Wholesaler/ Distributor
- Their business is growing rapidly, and they still rely on Excel files for data analytics. Excel files are hard to consume and not effective in generating insights. Also due to the lack of effective analytics, the company faced a major loss in Latin America.
- One of the challenges for AtliQ is its competitor which is a bigger company with having huge data analytics team that analyzes customers' demographics, consumption patterns, and income levels.
- Hence, to overcome these shortcomings the senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work.
- The senior executives gave their requirements of building five different dashboards specifically the Finance view, Sales view, Marketing view, Supply Chain view, and Executive view in Power BI. 
- A project kick-off session was held  to get a clear understanding of the project.

## Tools
- SQL
- Power BI Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)
- Project charter file

## Techniques Learnt
- What crucial queries should be addressed before project kick-off?
- Ensure data accuracy and reliability through effective validation strategies
- Utilize Power Query for seamless Extract, Transform, Load (ETL) processes for data preparation and data transformation
- Data modeling
- Apply DAX language for creating measures and calculated columns
- Using field parameters
- Using the selection tab to create Bookmarks
- Using Bookmarks to switch between two visuals
- Create user-friendly navigation using buttons and tabs
- Prevent zero division errors with the safe divide function
- Applying filters to the visuals
- Creating date table using m language
- Generate dynamic titles based on changing data using measures
- Highlight key indicators effectively with the New KPI card feature
- Conditional formatting of the values in visuals using icons and/or data bars
- Editing interactions between visuals as per requirements
- Publishing reports to PowerBI services
- Establish a personal gateway for automatic data refresh
- Create Power BI apps for enhanced functionality
- Streamline teamwork with effective collaboration, workspace, and access permissions in Power BI services

## Business related terms
- Gross price
- Pre and Post Invoice Deductions
- Net Invoice sales
- Net sales
- Cost Of Goods stock (COGS) 
- Gross Margin
- Net profit
- Fiscal Year
- Quarter-on-Quarter growth
- Year-on-Year Growth
- YTD - Year to Date
- YTG - Year to Go
- Net Error
- Forecast Accuracy
- Channel types: Direct, Retailer, Wholesaler/ Distributor
- Difference between Customer and Consumer

### Questions to ask at the start before building a dashboard
- What is the primary objective behind developing this Power BI dashboard?
- How will the success of this project be measured?
- What is the project deadline?
- Do stakeholders anticipate a preview before the official release?
- What specific expectations do stakeholders have for this project?
- Are there any concerns or fears among stakeholders regarding the development of this dashboard?
- Who will be the end users of this dashboard, and what purposes will it serve for them?
- What are the anticipated benefits or outcomes stakeholders hope to achieve through this project?
- What potential challenges or obstacles might arise during the development of this dashboard?
- What resources and data will be required to successfully build and implement this dashboard?
- Have stakeholders provided any input on the design and views of the dashboard?

After the project kick-off meetings, the data engineering team has given the data as per the request of the data analytics team, let’s explore them.

### Dataset Understanding
Data Cleaning and Data Exploration is the most crucial part of any data analysis project.

Dimension table: It is a database table that stores attributes that describe the facts in a fact table such as details of customers and products.
Fact table: The fact table contains business facts (or measures) such as data about transactions within a particular period. 

## Importing data into Power BI
- For this project, our data is stored in the MySQL database. To import the data from MySQL to Power BI we need to have the Database Access Credentials, select the server, and transform and load the data.

## Data Model
- Data modeling plays a key role and acts as a foundation for our report. All the visuals will be built upon the data model.
- Data models should be properly checked before moving on to the next step as mistakes would cause delays in project execution and stakeholders' dissatisfaction.
- Things to look out for while building a data model, refer to this page to get to know the good practices [Blog](https://addendanalytics.com/blog/data-modelling-best-practices/)
- In this project, we have used the snowflake data model.

<img src="https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Data_Model.png" class="center">

### Designing an Effective Dashboard
Based on the mock-ups received from our stakeholders, the data analyst's job is to design and build dashboards.

## Home view
The home view consists of buttons that will take users to a particular view page. 

- Info
- Finance View
- Sales View
- Marketing View
- Supply Chain View
- Executive View
- Top/ Bottom Products
- Support page
- Feedback page
- Attribution page

## Home Page
![Home Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Home_view.png)

## Info Page
![Info Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Info_tab.png)

## Finance View
![Finance Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Finance_view.png)

## Sales View
![Sales Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Sales_view.png)

## Marketing View
![Marketing Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Marketing_view.png)

## Supply chain View
![Supply Chain Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Supply_Chain.png)

## Executive View
![Executive Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Executive_view.png)

## Top/ Bottom Products
![Top/ Bottom Products](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/top_bottom_products.png)

## Support Page
![Support Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Support_tab.png)

## Feedback Page
![Support Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Feedback_tab.png)

## Attribution Page
![Support Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/snap_attribution.png)


## Project Insights
- Target data is a benchmark set by experienced management personnel and in this project, it is available for the year 2022 only and it gives a more accurate picture compared to the YoY change comparison. For this project, we have target data available for key metrics such as net sales, gross margin, and net profit for their market/ country.
- In comparison with Last year,
for the year 2022, net sales changed by +353.5%, gross margin changed by +373%, gross margin % changed by +4.37%, and net profit % changed by -110.8%.
- In comparison with Target,
for the year 2022, net sales changed -1.86%, gross margin changed -2.51%, gross margin % changed -0.66% and net profit % changed +1.47%
- Hence, we must consider a comparison of target data for our analysis.

#### Key Metrics:
For the year 2022,
In comparison with Target,
- Net sales drop is highest (-2.48%) in the APAC region and comparatively better (-1.13%) in the EU region.
- Gross margin drop is highest (-3.8%) in the NA region and comparatively better (-1.72%) in the EU region.
- Gross margin % drop is highest (-2.59%) in the NA region and comparatively better (0.56%) in the APAC region.
- Net Profit drop is highest (-3.3%) in the EU region and comparatively better (-0.36%) in the APAC region.
- Dell has been the market leader since 2018 as per the market share %. AtliQ gained a significant market share of 5.9% in 2022 based on robust net sales growth. 

#### Sales view and Marketing view:
-- Customer Performance:

For the year 2022,
In comparison with Target,
- GM % variance is 10% or higher, for customers such as Novus, Billa, Digimarket, Flawless Stores, Notebillig, and Otto.
- Net sales and gross margin generated by "Amazon" is the highest (497 Million ₹ & 182.77 Million ₹) among all customers and "Nova" generated the lowest net sales and gross margin (1.71 Million ₹ & 0.52 Million ₹) in the same period.
- GM % is highest (48.55%) for "Relief" customers and it is lowest for "Novus" (21.5%).
- Net profit and net profit margin % generated by the APAC region are the lowest (-281.16 Million ₹ & -14.62%) among all regions and the LATAM region generated comparatively better net profit and net profit margin % (-0.44 Million ₹ & -2.95%) in the same period.

-- Product Performance:

For the year 2022,
In comparison with Target,
- Net sales and gross margin generated by the segment "Notebook" is the highest (1580 Million ₹ & 600 Million ₹) among all segments and the "Networking" segment generated the lowest net sales and gross margin (38.4 Million ₹ & 14.8 Million ₹) in the same period.
- The net profit and net profit margin % generated by the segment "Notebook" is the lowest (-222.16 Million ₹ & -14%) among all segments and the "Networking" segment generated comparatively better net profit and net profit margin % (-5.27 Million ₹ & -13.72%) in the same period.

- AtliQ Hardware is in its expansion phase. Hence, a negative growth of net Profit and net profit % may not be the right metric to look at while analyzing its business growth as its main focus now is to gain a sizable amount of market share from its competitors and net sales and gross margin growth.

- Overall out of total gross sales, almost 50% accounts for deductions, and the rest 50% is net sales.
- Out of these net sales, 38% is Total COGS and the rest 62% is gross margin.
- Although the overall gross margin is +1,422 Million ₹ the operating expenses are on the higher side i.e., -1945 Million ₹ which together makes an overall negative net profit of -522 Million ₹.

#### Supply Chain view:

For the year 2022,
- Overall forecast accuracy % increased marginally by +1.2%, net error decreased by -362%, and absolute error decreased by -29.4% compared to last year.
- In the case of "Forward Stores", forecast accuracy % decreased from 50.7% to 10.7% in a year which resulted in Net Error % of -71.1%. Hence, they were not been able to cater to the high demand and went out of stock.
- In the case of "BestBuy", forecast accuracy % increased from 35.3% to 46.6% in a year which resulted in a Net Error % of 16.72. Hence, they were more than inventory.
- In the case of "Notebillig", forecast accuracy % increased from 18.8% to 42.7% in a year which resulted in a Net Error % of 1.31%. Hence, they were more than inventory. And, in the case of "Relief" stores, the forecast accuracy % is unchanged at around 52% for a year which results in a Net Error % of -0.14%. Hence, they were in an out-of-sell situation.
- A product segment called "Peripherals" which accounts for net error% (-32%) in a year results in making this segment out of stock. And, in a product segment called "Desktop" accounts for net error% (10.24%) in a year resulting in making this segment over inventory.

## Potential Decisions

#### Sales and Marketing Strategy:
- Customer Performance: Prioritize customers such as Novus, Billa, Digimarket, Flawless Stores, Notebillig, and Otto, where GM % variance is 10% or higher. A higher GM % variance indicates that GM % growth targets are not being met for these customers. Devote attention to these accounts to identify and address factors contributing to the variance and implement corrective measures.
- Product Performance: Focus efforts on the "Notebook" segment, which has the highest net sales and gross margin. Evaluate strategies to improve the net profit and net profit margin for this segment.
  
#### Regional Focus:
- Address challenges in the APAC region, where there are significant drops in net sales, gross margin, gross margin %, net profit, and net profit %.
- Replicate successful strategies from the EU region, which has comparatively better performance across key metrics.

#### AtliQ Hardware Expansion:
- Acknowledge the negative growth in net profit and net profit % for AtliQ Hardware during its expansion phase. Emphasize gaining market share and evaluate success based on net sales and gross margin growth.

#### Cost Management:
- Analyze and optimize operating expenses, which contribute to an overall negative net profit. Identify cost-cutting measures without compromising essential functions.

#### Supply Chain Optimization:
- Enhance forecast accuracy, particularly for stores like "Forward Stores" with a drastic decrease in accuracy that led to an out-of-stock situation. Also, implement measures to avoid excess inventory.
- Address issues with the "Peripherals" segment, which experienced a net error % of -32%, leading to an out-of-stock situation. Evaluate and adjust inventory levels for the "Desktop" segment with a net error % of 10.24% which leads to excess inventory.
