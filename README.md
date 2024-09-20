# PWC Virtual Internship

## Background and Project Overview

This project is part of PwC Switzerland's Power BI in Data Analytics Virtual Internship, showcasing the application of digital tools for data visualization, automation, and data cleansing to address common business challenges. It includes a series of Power BI dashboards focused on:

- **Call Centre Trends**
- **Customer Retention**
- **Diversity & Inclusion**

Each dashboard delivers actionable insights into different aspects of business operations and strategic planning, aiding PwC Switzerland and its clients in improving operational efficiency, enhancing customer loyalty, and fostering a more inclusive workplace.

By utilizing detailed data analysis and visualization, the project aims to drive informed decision-making while identifying opportunities for improvement and innovation.

### Disclaimer
This project is completed using **Tableau** for data visualization and analysis. Although Tableau is the tool of choice for this project, the insights and visualizations created can be adapted to other platforms if needed. All visualizations and analyses will be shared in **Tableau-compatible formats**.

## Dashboards and Key Insights

### Call Centre Trends

The first dashboard provides a comprehensive overview of key call centre metrics, including customer satisfaction, call volumes, and agent performance. This visualization helps identify areas for improvement in call centre operations, enabling more effective management and support.

Access [here](https://public.tableau.com/app/profile/tiffany.hou8743/viz/CallCenterTrends_17267235969210/Dashboard1) for live and interactive dashboards.

<img width="1001" alt="Call Center Trends" src="https://github.com/user-attachments/assets/8b50d533-f44c-4989-a607-f6d0479dd528">

#### Total Calls and Performance:
Out of the 5,000 total calls handled by eight agents, 81% were answered, and 73% were resolved. The average satisfaction rating is 3.4 out of 5, which indicates room for improvement. The average speed of answer is 68 seconds, suggesting moderate efficiency.

#### 1. Topic Distribution:
- The distribution of calls across topics is relatively even, with no significant differences in volume.

#### 2. Agent Performance:
- **Joe** and **Stewart** handled fewer than 600 total calls, answered fewer than 500 calls, and resolved fewer than 450 calls, while the other agents exceeded these numbers.
- **Jim** handled the most total, answered, and resolved calls, while **Stewart** had the fewest across all categories.
- Satisfaction scores by topic ranged between 3.2 and 3.7, with no major deviations. **Martha** achieved the highest satisfaction rating of 3.7 in streaming, while **Joe** had the lowest at 3.2. **Dan** performed best in technical support, while **Becky** had the lowest rating in this category.

#### 3. Resolved Calls by Topic:
- **Jim** led in contract-related calls with 110 resolved, while **Joe** only managed 75.
- **Dan** excelled in technical support, resolving 106 calls, compared to **Greg**, who handled only 79.
- **Becky** resolved 105 streaming calls, while **Stewart** only resolved 77.

#### 4. Call Duration:
- **Greg** had the shortest average call duration for admin support (2.7 minutes) but the longest for streaming.
- **Diane** showed a similar pattern, with the shortest duration for admin support and the longest for contract-related calls.
- Other agents' call durations were fairly consistent across topics (< 0.5min difference).

#### 5. Call Volume by Time:
- Call volume dips at 2 PM after peaking at 1 PM, and then gradually increases again, reaching another peak towards the end of the day at 5 PM.

#### 6. Satisfaction and Speed of Answer:
- Satisfaction ratings and speed of answers show little variation among agents, with **Martha** receiving the highest rating and **Joe** the lowest. 
- The difference in speed of answer between the agents is minimal (0.08 minutes), and there is no clear correlation between satisfaction ratings and the number of resolved or answered calls nor speed of answer.

#### Recommendations:

1. **Expert Mentorship:** Agents excelling in specific areas, like **Martha** in streaming and **Dan** in technical support, should mentor agents with lower performance, such as **Joe** and **Becky**.

2. **Targeted Coaching:** **Stewart** and **Joe** should receive additional coaching to improve their overall call handling and resolution rates.

3. **Optimize Scheduling:** Adjust staffing during peak times, particularly around 1 PM, to reduce average speed of answer and maintain service quality.

4. **Distribute Workload:** Assign more calls to agents in their weaker areas to build experience, with guidance from high performers.

5. **Standardize Call Durations:** Investigate agents' varying call durations to establish more consistent handling times across topics.

### Customer Retention

This dashboard, developed in response to a request from the telecom's Retention Manager, highlights key metrics related to customer loyalty and retention. It visualizes data to predict customer churn and identifies potential strategies to improve retention rates.

Access [here](https://public.tableau.com/app/profile/tiffany.hou8743/viz/CustomerRetentionAnalysis_17267754745280/ChurnAnalysis) for live and interactive dashboards.

<img width="1001" alt="Customer Retention" src="https://github.com/user-attachments/assets/12bcb694-fff2-4a5e-8c9f-42108c76a7b8">

#### Total Customers and Performance: 
The analysis is based on 7,043 customers, with a churn rate of 26.5%. Of these customers, 48.3% have a partner, 16.2% are senior citizens, and 30% have dependents.

#### 1. Churn Rate and Demographics:
- **Customers without a partner** are twice as likely to churn compared to those with a partner (**35%** vs. **17%**).
- **Non-senior citizens** are three times more likely to churn, making up **64%** of churners, while only **7%** of senior citizens churn.
- **Customers without dependents** are four times more likely to churn, representing **48%** of churners, compared to **5%** for those with dependents.

#### 2. Contract Type:
- **Month-to-month contracts** have the highest churn rate (**23%**), while **one-year** and **two-year contracts** have significantly lower churn rates (**2%** and **1%**, respectively).

#### 3. Payment Method:
- The **electronic check** payment method has the highest churn rate (**15%**), while other methods, such as **mailed checks**, **bank transfers**, and **credit card payments**, have lower churn rates (all below **5%**).

#### 4. Charges and Tickets:
- Customers with higher **average total charges** (around **$2,555**) tend to churn more than those with lower total charges (**$1,532**).
- Churners also tend to have more **tech tickets** (**2,173**) compared to non-churners, who have fewer (**782**). Conversely, churners have fewer **admin tickets** (885 vs. 2,747), indicating that technical issues could be contributing to churn.

#### 5. Services Impacting Churn:
- Churners are less likely to subscribe to services like **online security** (16% vs. 33%), **device protection** (29% vs. 36%), and **tech support** (18% vs. 34%). This lack of service adoption may contribute to the higher number of tech tickets.
- **Phone service** is retained by **91%** of all customers, with no major difference between churners and non-churners (90%).
- **Multiple lines**, **streaming TV**, and **streaming movies** have slightly higher churn rates compared to other services, but remain popular among both churners and non-churners.

#### Recommendations:

1. **Encourage Long-Term Contracts:** Since **month-to-month contracts** have the highest churn rate, offer incentives for customers to switch to **one-year** or **two-year contracts** (e.g., discounts or loyalty rewards).

2. **Improve Technical Support:** The high number of tech tickets among churners suggests dissatisfaction with technical issues. Enhancing **technical support** availability and quality may help reduce churn.

3. **Promote Service Add-ons:**  Encourage customers to adopt additional services like **online security**, **device protection**, and **tech support**, as churners have lower subscription rates to these services. This could also reduce the number of tech-related issues and tickets.

4. **Targeted Retention Campaigns for Key Demographics:**  Create targeted campaigns for customers **without partners** or **dependents**, who show higher churn rates. Offer personalized services or benefits to encourage retention. Since **Senior citizens** churn less, so continuing to offer tailored services, such as specialized tech support for older customers, may help maintain low churn rates in this demographic.

5. **Payment Method Optimization:** Customers using **electronic checks** show higher churn rates. Offer more convenient and reliable payment methods like **automatic payments via bank transfers or credit cards**, along with discounts to encourage adoption.

6. **Monitor High-Cost Customers:** Since customers with higher total charges tend to churn more, consider offering **tiered pricing** or **loyalty rewards** for high-spending customers to retain them, such as discounts on additional services or premium support.


### 3. Diversity & Inclusion

This dashboard focuses on the telecom client's goal of improving gender balance at the executive management level. It provides a clear visualization of diversity and inclusion metrics, offering insights into current trends and areas for action.

Access [here](https://public.tableau.com/app/profile/tiffany.hou8743/viz/DiversityInclusion1/Dashboard1) and [here](https://public.tableau.com/app/profile/tiffany.hou8743/viz/DiversityInclusion_17267751564930/Dashboard2) for live and interactive dashboards.

<img width="1001" alt="Diversity Inclusion 1" src="https://github.com/user-attachments/assets/08b101ba-1681-423e-ab9b-36a57b9945f1">

<img width="1001" alt="Diversity Inclusion 2" src="https://github.com/user-attachments/assets/1d1174fe-3ea8-486c-b6a1-cd562026af58">




