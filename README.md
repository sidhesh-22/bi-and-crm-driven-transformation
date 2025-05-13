# BI-and-CRM-driven-transformation

## Table of Contents

- [Project Overview](project-overview)
- [Data Source](data-source)
- [Major steps followed](major-steps-followed)
- [Insights and Findings](insights-and-findings)
- [Conclusion and further scope](conclusion-and-further-scope)


### Project Overview

This project basically looks at the challenges faced by an electronics retailer (Gadget Geeks) and proposes appropriate solutions using BI and a CRM platform. So mock datasets were used which represented the actual data, and BI dashboards were presented to showcase the power of having unified data and drawing meaningful insights from it. Also Salesforce CRM demonstration was proposed to the business to portray how beneficial a CRM platform can be to any business.


![image](https://github.com/user-attachments/assets/906b486f-b1f0-4e7b-82ad-9a7e730e033a)


### Data Source

All the datasets used in this project have been taken from Kaggle.


### Major steps followed

1. Fetching all the required datasets from Kaggle.
2. All the project plan was first conceptualised using a Miro Whiteboard, as to what all has to be achieved and how it will be implemented.
3. Created dummy marketing campaigns in Salesforce using the 'Campaigns' object.
4. Created cases under the 'Cases' section in Salesforce to demonstrate Case Management.
5. Salesforce 'Flows' was used to automate routine communication processes. A Record-Triggered Flow was set up to send an automated confirmation email as soon as a new ticket is created. 
6. Dashboards were created in Tableau to demonstrate the use of BI.
7. 3 different dashboards about Sales, Marketing, and Customer Support Tickets were created in Tableau.


Below is a snapshot of a Record Trigger Flow implemented in Salesforce.


![image](https://github.com/user-attachments/assets/13723d91-26c8-4ab3-8cf0-93f470b02e11)



### Insights and Findings

1. Customer Support Tickets Dashboard presents a comprehensive, filterable view to understand service patterns and resolution quality over time. It enables the operations team to improve agent performance and reduce churn through faster, better support. In the customer service domain, the average ticket resolution time dropped to 3.5 hours, and more than 70% of issues were resolved in a single interaction (as shown in the Tableau dashboard).
   

<img width="1200" alt="Customer Support Ticket Dashboard" src="https://github.com/user-attachments/assets/fb0387a4-847c-4c8c-9f01-435d253b1b05" />



2. The second dashboard was created for the marketing department to analyze campaign success, channel ROI, and audience engagement. This dashboard supports optimization of current and future campaigns based on real performance data. In marketing, the deployment of campaign tracking through Salesforce, along with Tableau’s visual breakdown of spend vs. performance, empowered the team to identify the top 5 converting campaigns and optimize budget distribution.


<img width="1205" alt="Marketing Dashboard" src="https://github.com/user-attachments/assets/6020e333-1521-4330-99da-8575bea8d02b" />



3. The final dashboard targets the executive and sales management teams. It visualizes product performance, revenue trends, and customer behavior patterns across regions. Sales operations also benefited. Managers gained real-time visibility into monthly revenue, customer demographics, and product-wise performance, enabling them to plan promotions more effectively. For example, the “Weekend vs Weekday” sales insights revealed a 42% higher conversion rate on weekends, leading to the decision to time future campaigns around those high-traffic periods.


<img width="1201" alt="Sales Dashboard" src="https://github.com/user-attachments/assets/b52c04a9-bf76-4575-9258-382653f67647" />



4. The integration of CRM automation flows, such as email notifications for ticket creation and resolution, closed a major communication gap and ensured timely updates to customers, significantly improving customer experience and retention.




### Conclusion and further scope

- This venture turned into a deep and precious mastering revel in in enforcing cease-to-give up Business Intelligence and CRM workflows.
- CRM use cases can include lead nurturing and upselling workflows in the future.
- Introduce AI-based sentiment analysis on support tickets to anticipate churn risk.
- Incorporate predictive analytics in Tableau using time-series forecasting to project sales and ticket volumes.
- Migrate datasets to a central cloud-based warehouse for better scalability and automation.
