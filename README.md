# Lima Ride Operation Analysis (Power BI)
**Dark Mode**

<img width="356" height="223" alt="First Page (dark)" src="https://github.com/user-attachments/assets/884e2b0f-800e-48c9-9ce5-89385e8a84a6" /> <img width="348" height="220" alt="Second Page (dark)" src="https://github.com/user-attachments/assets/b9d8a4f8-dead-4632-be03-51386868fbad" />

**Light Mode**

<img width="360" height="222" alt="First Page (light)" src="https://github.com/user-attachments/assets/e380fd45-6a3b-460a-b2aa-3532dc8c8742" /> <img width="357" height="222" alt="Second Page (light)" src="https://github.com/user-attachments/assets/f7d53b40-972c-498b-906f-c21fe9ef3e87" />


### Project Overview
Ride-sharing companies generate thousands of operational records every day, but raw data alone cannot answer important business questions.
Lima Ride wanted to understand how its business evolved between June 2021 and December 2024, identify operational bottlenecks, evaluate driver performance, and uncover opportunities to improve customer retention and revenue growth.

This project involved cleaning and validating operational data, designing a dimensional data model, creating DAX measures, and developing an interactive Power BI dashboard that transforms raw ride data into actionable business insights.

### Skills Demonstrated
This project demonstrates practical experience in:
- Power Query
- Data Cleaning
- Data Validation
- Data Modelling
- Star Schema Design
- DAX
- KPI Development
- Business Intelligence
- Dashboard Design
- Data Storytelling
- Business Recommendation Development

### Business Problem
Management needed answers to questions such as:
* Is revenue growing consistently over time?
* Which cities contribute the most revenue?
* Where are ride cancellations highest?
* Which drivers consistently perform well?
* Which drivers qualify for performance bonuses?
* Which payment methods are preferred by loyal riders?
The objective was to convert operational data into information that supports strategic decision-making.

### Project Objectives
The analysis focused on:
* Measuring revenue performance across four years
* Evaluating ride demand and operational efficiency
* Measuring driver productivity and consistency
* Assessing rider retention
* Supporting performance-based bonus decisions
* Understanding payment behaviour

### Dataset Overview
The project consists of four related datasets:
- Ride Transactions: Contains operational ride information
- Payments: Contains payment information
- Riders: Contains rider (customer) registration information
- Drivers: Contains driver information

### Data Preparation
Several data quality issues were resolved before analysis.
Cleaning activities included:
* Removing duplicate records
* Handling missing payment information
* Standardising inconsistent city names
* Validating ride fares and driver ratings
* Separating date and time fields for analysis
* Merging payment data with ride transactions to create a single ride fact table
* Building a Star Schema for efficient reporting
* Creating a comprehensive Date Dimension

### Data Model
The final model follows a Star Schema consisting of:
**Fact Table**
- Rides Fact
**Dimension Tables**
- Drivers
- Riders
- Date
This structure simplifies DAX calculations, improves report performance, and supports scalable analysis.

### Dashboard Overview
The dashboard was designed in both Dark Mode and Light Mode to demonstrate dashboard design flexibility while maintaining the same analytical experience.

The report is divided into two pages:
**Executive & Operations Overview**
Focuses on:
* Revenue performance
* Booking trends
* Driver ratings
* Ride demand
* Cancellation rate
* City performance
* Time-of-day analysis

**Driver & Customer Intelligence**
Focuses on:
* Driver consistency
* Driver bonus qualification
* Longest ride analysis
* Driver ratings
* Customer behaviour
* Operational performance

### Key Business Questions Answered
The dashboard answers several business-critical questions, including:
- Which quarter recorded the strongest revenue growth?
- Which cities generate the highest revenue?
- Which cities experience the highest cancellation rates?
- Which drivers consistently complete the most rides?
- Which drivers qualify for performance bonuses?
- Which riders remained active years after signing up?
- Which rides covered the greatest distance?

### Executive Insights
**Revenue Growth**
Revenue demonstrated steady growth throughout the analysis period, highlighting increasing adoption of the platform across major operating cities.

**Operational Performance**
Cancellation rates varied slightly across cities, indicating opportunities to optimise driver allocation and improve service reliability.

**Driver Performance**
Several drivers consistently maintained high ride volumes alongside strong customer ratings, making them suitable candidates for incentive programmes.

**Customer Retention**
A meaningful number of riders continued using the platform years after signup, suggesting healthy customer retention while also highlighting opportunities to improve long-term engagement.

**Payment Behaviour**
Digital payment methods dominated transactions among frequent riders, suggesting continued investment in cashless payment experiences could improve operational efficiency.

### Business Recommendations
Based on the findings, Lima Ride should consider:
* Expanding operations in high-performing cities
* Investigating operational causes of cancellations in underperforming locations
* Introducing targeted incentives for high-performing drivers
* Strengthening customer retention initiatives for newer riders
* Encouraging digital payments through rider rewards and promotions
* Monitoring quarterly performance to identify seasonal demand patterns

### Dashboard Preview
**Executive Dashboard (Dark Mode)**

<img width="556" height="323" alt="First Page (dark)" src="https://github.com/user-attachments/assets/01dab69c-04ff-46eb-af0b-2fad390dfdc3" />

**Driver Dashboard (Dark Mode)**

<img width="548" height="320" alt="Second Page (dark)" src="https://github.com/user-attachments/assets/15664b27-de14-48ea-a4a2-3b23d56a3b9c" />

**Executive Dashboard (Light Mode)**

<img width="560" height="322" alt="First Page (light)" src="https://github.com/user-attachments/assets/7524b16d-7014-4cf4-9559-e76c5fa190f5" />

**Driver Dashboard (Light Mode)**

<img width="557" height="322" alt="Second Page (light)" src="https://github.com/user-attachments/assets/1ab8c58a-a518-4838-9be3-0d90d3ff113e" />


### Conclusion
This project demonstrates how operational ride data can be transformed into meaningful business intelligence that supports strategic decision-making.

Rather than simply reporting historical performance, the dashboard highlights operational strengths, identifies areas for improvement, and provides actionable insights that management can use to improve revenue, optimise driver performance, reduce cancellations, and strengthen customer retention.

### What I Learned
This project reinforced the importance of designing dashboards around business decisions rather than simply visualising data. From resolving one-to-one relationship challenges during data modelling to building KPIs that answered operational questions, every step focused on helping stakeholders make informed decisions. It also strengthened my ability to translate complex datasets into clear, actionable insights through effective storytelling and dashboard design.
