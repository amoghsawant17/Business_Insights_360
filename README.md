# Business Insights 360

## Project Overview

AtliQ Hardware has been growing rapidly in recent years, and they have decided to implement data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data-driven decisions. This project is hoped to give answers to the questions of stakeholders in terms of all aspects like Finance, Sales, Marketing, and Supply Chain.

I worked on this project by following the Codebasics PowerBI Course, Link to the course is [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)

## Tools

- SQL
- PowerBI Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)
- Project charter file

## PowerBI techniques Learnt

- What are all the questions that should be asked before starting the project
- Creating calculated columns
- creating measures using the DAX language
- Data modeling
- Using Bookmarks to switch between two visuals
- Page navigation with buttons
- Using the divide function to prevent zero division errors
- creating data table using m language
- Dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting of the values in visuals using icons or background color
- Data validation techniques
- PowerBi services
- Publishing reports to PowerBi services
- Setting up a personal gateway to set up the auto-refresh of data
- PowerBi App creation
- Collaboration, workspace, and access permissions in PowerBi services
- And more 😅

## GitHub 

- Uploading Large size files using GitHub LFS
- Tracking the particular type of file extensions for LFS

## Business related terms

- Gross price
- Pre-Invoice Deductions
- Net Invoice sales
- Post-Invoice Deductions
- Net sales
- Cost Of Goods Sold (COGS) 
- Gross Margin
- Net profit
- YTD - Year to Date
- YTG - Year to Go
- Channel types: Direct, Retailer, Wholesaler/ Distributor
- Difference between Customer and Consumer

## Company’s background

AltiQ Hardware is a company that has grown vastly in recent years, and opened business all over the globe. It is a company that sells, computers and computer accessories through three mediums/channel

- Retailer
- Direct
- Wholesaler/ Distributor

Recently the company has faced an unforeseen loss by opening a store in America based on surveys, intuition, and some Excel analysis also the company’s competitors has a handful of analytics team to perform analysis and make data-driven decision. So, the AltiQ hardware has no other option other than building its analytics team for data-driven insights and decisions in the future to survive better in the industry. 

Project kick-off session, where you should get clear of what and why this project is and all other questions you have with regards to the project

### Questions to ask before starting with the dashboard

- What is the objective of building this PowerBi dashboard?
- In what terms the success of this project will be measured?
- What will be the deadline of the project?
- do the stakeholders expect a preview before the actual release?
- What are all the hopes stakeholders have out of this project?
- what are all the fears the stakeholders have in terms of building this dashboard?
- Who will be using this dashboard and for what purpose?
- what are all expectations the stakeholders have, by the completion of this project?
- What can go wrong while building this project?
- what are all the resources/ data needed to build this dashboard?
- is there any input from stakeholders in terms of design and views of the dashboard?

After the project kick-off meetings, the data engineering team has given the data as per the request of the data analytics team, let’s explore them.

### Dataset Understanding

Data Cleaning and Data Exploration is the most crucial part of any data analysis project.

Dimension table: It is a database table that stores attributes that describe the facts in a fact table such as details of customers and products.

Fact table: The fact table contains business facts (or measures) such as data about transactions within a particular period. 

## Importing data into PowerBI

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
- Support

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
## Support

![Support Page](https://github.com/amoghsawant17/Business_Insights_360/blob/main/Views_Snaps/Support_tab.png)

you can find the full report file here : [Report](https://github.com/Naveen-S6/Business_Insights_360/blob/main/Report/360.pbix)


## Project Insights

