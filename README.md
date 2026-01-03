**Boston Women Entrepreneurship Incubator Tracker**

A centralized data system designed to track, manage, and analyze startups, mentors, investors, and events for incubator program insights and data-driven decision-making.

**📌 Project Overview**

Incubator programs often manage complex, interconnected data across startups, mentors, investors, funding, and events. This project focuses on building an end-to-end data system that integrates relational and NoSQL databases to enable structured tracking, flexible querying, and actionable analytics for incubator operations.
The system supports operational reporting, performance analysis, and engagement tracking across multiple entities in a scalable and well-modeled data architecture.

**🎯 Objectives**

•	Design a robust data model to represent real-world incubator operations

•	Enable efficient tracking of startups, mentors, investors, and events

•	Automate data querying and analysis for operational insights

•	Support both structured and semi-structured data use cases

•	Generate insights to inform funding, engagement, and program planning

**🗂️ Data Modeling & Architecture**

Relational Database (MySQL)

•	Designed EER and UML diagrams to model entity relationships

•	Implemented a fully normalized schema to reduce redundancy and improve integrity

•	Core entities include:

  o	120 startups
  
  o	80 mentors
  
  o	60 investors
  
  o	60 events

•	Junction tables used to manage many-to-many relationships

NoSQL Database (MongoDB)

•	Modeled semi-structured data using collections for flexible querying

•	Implemented 14 core and junction collections

•	Enabled efficient aggregation across funding, participation, and engagement data

**🔄 Data Pipelines & Automation**

•	Developed Python-based automation scripts to execute:

  o	10+ simple and advanced MySQL queries
  
  o	Aggregation and filtering logic

•	Performed exploratory data analysis (EDA) on operational data

•	Generated visual insights using Matplotlib and Seaborn

**📊 Analytics & Insights**

The system supports analysis such as:

•	Identification of top-performing startups

•	Detection of high-impact mentors

•	Analysis of high-growth industries

•	Tracking of investor engagement patterns

•	Evaluation of event participation trends

•	Funding distribution analysis across startups and industries

These insights help incubator stakeholders make data-driven decisions related to program planning, mentorship allocation, and funding focus.

**🛠️ Technologies Used**

**Databases**

•	MySQL

•	MongoDB

**Programming**

•	Python

**Libraries**

•	Pandas

•	Matplotlib

•	Seaborn

**Data Modeling**

•	EER Diagrams

•	UML Diagrams

**📈 Project Impact**

•	Centralized data management for incubator operations

•	Improved visibility into startup performance and engagement

•	Enabled scalable analytics across relational and NoSQL systems

•	Demonstrated real-world application of database design and data analytics concepts

**🚀 Key Takeaways**

•	Strong application of database design principles

•	Practical integration of SQL and NoSQL systems

•	End-to-end analytics workflow from modeling to insights

•	Business-focused analysis aligned with stakeholder needs

**▶️ How to Run**

1.	Clone the repository

2.	Set up MySQL and MongoDB instances

3.	Execute SQL scripts to create tables and seed data

4.	Run Python notebooks/scripts to generate queries and visual insights
