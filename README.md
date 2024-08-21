# Building a Data-Driven Income Statement Dashboard in Power BI

## Table Of Content
- [Project Overview](#project-overview)
- [Data Tools](#data-tools)
- [Data Modelling](#data-modelling)

### Project Overview
Creating a compelling data visualization is more than just arranging numbers on a screen; it's about telling a story that drives insight and action. In this project, I developed an income statement dashboard for a fictional organization, capturing its financial performance over the past two years. Below, I'll walk you through the key stages of this project, from data preparation to the final design, showcasing how tools like Power BI, DAX, and effective dashboard design can be leveraged to create impactful data stories.

### Data Tools
I started the project using Power query to handle the ETL aspect of the project. I like Power Query because it's a point and click tool which makes cleaning data fast and efficient but on some rare occassions you might need to apply the "M" language code which is Power Query main language. After Power Query I move into Power BI where i model my data, build my measures and visualize them with charts and cards.

### Data Model
This primarily involves connecting my fact table to my dimension table using a primary key or a column they have in common. This helps to create a connection between my tables and i can make meaning of each data.

### Extract, Tranform, Load (ETL)
The first step in building this dashboard involved gathering and transforming the necessary financial data. The data was sourced from various financial records, including revenue streams, costs, expenses, and taxes. Using Power BI's Power Query Editor, I performed several transformations to ensure the data was clean and structured correctly.

![Power Query Editor](https://github.com/user-attachments/assets/62aa7343-ca1c-405f-a5bf-66df777c5cb8)


### Key steps in the ETL process:

- Extraction: Financial data from multiple sources were imported into Power BI.
- Transformation: This involved cleaning the data by removing duplicates, handling missing values, and ensuring consistency in data types. Calculated columns were created to derive necessary metrics such as Net Income and EBIT.
- Loading: Once transformed, the data was loaded into Power BI’s data model, ready for further analysis.

### DAX in Power BI
DAX (Data Analysis Expressions) played a critical role in enhancing the analytical capabilities of the dashboard. With DAX, I created several measures that allowed for dynamic calculations, making the dashboard interactive and responsive to user inputs.

### Some of the key DAX measures include:

- Revenue Growth: A measure to calculate the percentage change in revenue year-over-year.
- Net Income Margin: This measure calculates the ratio of net income to total revenue, providing insight into profitability.
- Variance Analysis: DAX was used to compare current year data with the previous year, highlighting areas with significant changes.
  These measures not only enriched the dashboard with meaningful metrics but also enabled the users to drill down into specific financial details.

![Dashboard Design](https://github.com/user-attachments/assets/a0e0c26d-e202-4ef0-8d68-7fc293d3453c)

### Conclusion
This income statement dashboard showcases how Power BI can be used to turn raw financial data into actionable insights. From ETL processes to DAX calculations and thoughtful design, every step was aimed at making the data accessible, understandable, and useful for decision-makers.
By combining technical expertise with creative design, I was able to create a tool that not only displays data but also tells the story of an organization's financial journey over the past two years.
