# PWC Virtual Internship

## Background and Project Overview

This project is part of PwC Switzerland's Power BI in Data Analytics Virtual Internship, showcasing the application of digital tools for data visualization, automation, and data cleansing to address common business challenges. It includes a series of Power BI dashboards focused on:

- **Call Center Trends**
- **Customer Retention**
- **Diversity & Inclusion**

Each dashboard delivers actionable insights into different aspects of business operations and strategic planning, aiding PwC Switzerland and its clients in improving operational efficiency, enhancing customer loyalty, and fostering a more inclusive workplace.

By utilizing detailed data analysis and visualization, the project aims to drive informed decision-making while identifying opportunities for improvement and innovation.

### Disclaimer
This project is completed using **Tableau** for data visualization and analysis. Although Tableau is the tool of choice for this project, the insights and visualizations created can be adapted to other platforms if needed. All visualizations and analyses will be shared in **Tableau-compatible formats**.

## Dashboards and Key Insights

### Call Center Trends

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

---

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

---

#### Recommendations:

1. **Encourage Long-Term Contracts:** Since **month-to-month contracts** have the highest churn rate, offer incentives for customers to switch to **one-year** or **two-year contracts** (e.g., discounts or loyalty rewards).

2. **Improve Technical Support:** The high number of tech tickets among churners suggests dissatisfaction with technical issues. Enhance **technical support** availability and quality and encourage customers to adopt additional services like **online security**, **device protection**, and **tech support**, as churners have lower subscription rates to these services..

3. **Targeted Retention Campaigns for Key Demographics:**  Create targeted campaigns for customers **without partners** or **dependents**, who show higher churn rates. Since **Senior citizens** churn less, so continuing to offer tailored services to help maintain low churn rates.

4. **Payment Method Optimization:** Customers using **electronic checks** show higher churn rates. Perhaps switching to **automatic payments via bank transfers or credit cards** could help, along with discounts to encourage adoption.

5. **Monitor High-Cost Customers:** Since customers with higher total charges tend to churn more, consider offering **tiered pricing** or **premium support** for high-spending customers to retain them.


### Diversity & Inclusion

This dashboard focuses on the telecom client's goal of improving gender balance at the executive management level. It provides a clear visualization of diversity and inclusion metrics, offering insights into current trends and areas for action.

Access [here](https://public.tableau.com/app/profile/tiffany.hou8743/viz/DiversityInclusion1/Dashboard1) and [here](https://public.tableau.com/app/profile/tiffany.hou8743/viz/DiversityInclusion_17267751564930/Dashboard2) for live and interactive dashboards.

<img width="1001" alt="Diversity Inclusion 1" src="https://github.com/user-attachments/assets/08b101ba-1681-423e-ab9b-36a57b9945f1">

<img width="1001" alt="Diversity Inclusion 2" src="https://github.com/user-attachments/assets/1d1174fe-3ea8-486c-b6a1-cd562026af58">

#### Total Employee and Performance: 
There are 500 employees (295 male, 205 female) with an average performance rating of 2.5 across the organization - moderate overall performance.

#### 1. Employee Demographic:
- **Gender Distribution:** Males represent **59%** of the workforce, while females make up **41%**. This indicates a moderate gender imbalance, particularly in higher job levels.
- **Age Distribution:** The majority of employees are between **20-39 years old**, with the most significant group being aged **20-29** (44.6%).
  - Males dominate the younger age groups, with **24%** of 20-29-year-olds being male compared to **20.6%** female, and a similar pattern is observed in the 30-39 age group. This is consistent with the overall larger male population in the company.
  - **Junior Officers** are predominantly young, with **94.67%** aged **20-29**, indicating that most entry-level employees are early in their careers.
  - **Senior Officers** and **Managers** fall mainly between **30-49 years old**, with **83.54%** of managers aged **40-49**, suggesting that mid-level roles are typically held by more experienced employees.
  - **Executives** are largely older, with **68.42%** aged **50-59**, reflecting that most leadership roles are occupied by those in the later stages of their careers.
  - **Directors** are primarily aged **40-49** (**57.58%**), showing that leadership typically starts in this age range.

- **Nationality:**:
  - **52.8%** of employees are from **Switzerland**, while **44.8%** come from other **European** countries, reflecting a mostly European workforce.
  - A small minority (**0.4%**) are from the **Middle East**, indicating limited geographical diversity beyond Europe.

- **Job Level Distribution:**:
  - **Junior Officers** make up the largest group, with a near-even split between males (**17.2%**) and females (**20.1%**), suggesting balanced gender representation at entry levels.
  - **Senior Officers** and **Managers** are predominantly male, with males holding **11.9%** of manager roles and   **10.2%** of senior officer positions, compared to females at **5.5%** and **11.0%**, respectively.
  - **Executives** have the lowest representation, and directors are mostly male (**6.4%** male, minimal female representation).

#### 2. Employee Turnover and Retention:
- **Turnover Rate:** Overall turnover is **9.4%**, with **female turnover slightly higher.
  - **Leaver Distribution by Gender:** Males represent **55.3%** of total leavers, and females make up **44.7%**, reflecting the overall workforce ratio. This suggests no gender-specific issue with turnover, but it highlights the importance of retention strategies for both genders.
- **By Job Level:**
  - **Junior officers** show the highest turnover, with **17.2%** of males and **20.1%** of females leaving. This high turnover rate could indicate dissatisfaction at entry-level positions, possibly due to a lack of advancement or growth opportunities.
  - **Senior officers and managers** have significantly lower turnover rates, reflecting more stability at higher job levels.
- **Leaver by Department:** 
  - **Operations** and **Sales & Marketing** have the highest turnover, with both departments seeing a disproportionate number of junior officer leavers. This suggests challenges in retaining junior staff in operational roles.

#### 3. Hiring and Promotion:
- **New Hires FY20:** There were **66 new hires** in FY20, almost evenly split between genders (**32 male**, **34 female**), indicating good gender diversity in hiring practices.
- **Departmental New Hires:**
  - The highest number of hires occurred in **Operations** (**29 hires**), followed by **Sales & Marketing** and **Internal Services**. Departments like **HR** and **Finance** had minimal hiring (1 hire each), possibly reflecting lower growth or recruitment needs.
- **Promotion Rates and Distribution:**
  - **FY20:** Promotion rates show a clear gender disparity, with **9.5%** of males promoted compared to only **3.9%** of females. This imbalance is slightly addressed in **FY21**, with male promotion rates at **11.2%** and female promotion rates increasing to **8.8%**, though the gap remains.
  - In **FY20**, 28 males were promoted compared to just 8 females, while in **FY21**, 33 males were promoted compared to 18 females. The trend shows a gender imbalance in career progression.

#### 4. Comparative Analysis:
- **Average Performance Rating by Gender:**
  - Performance ratings are almost identical across genders. These minimal differences suggest that performance evaluations are not influenced by gender, but the overall performance scores seem relatively low, indicating a potential need for performance improvement programs across the organization.
- **Average Performance Rating by Department:**
  - There isn't much difference across departments. **Strategy** stands out with the highest average performance rating (**2.6**), while **Finance** and **HR** departments have lower performance ratings, hovering around **2.4**. 
- **PRA (Performance Review Analysis) Status by Department:**
  - **Operations** has the highest number of "Even" ratings (**182**), indicating consistent performance review practices.
  - **Sales & Marketing** displays the most significant disparity, with **41 "Uneven – Men Benefit"** ratings, raising concerns about gender bias in performance reviews within this department.
  - **Internal Services** has **47 "Even"** ratings but also shows **10 "Uneven – Men Benefit"**, indicating some imbalance.
  - **Finance** and **HR** both show **15 Inconclusive** ratings, indicating uncertainty in their review practices.


---

#### Recommendations:

1. **Improve Career Progression for Females:** Female promotion rates are consistently lower than males. Implement targeted leadership development programs and mentorship opportunities for women and ensure equal advancement opportunities.

2. **Address High Turnover Among Junior Officers:** Enhance retention efforts through career progression initiatives, mentorship, and addressing potential workload concerns for junior employees in these departments.

3. **Increase Diversity at Leadership Levels:**  While females are well-represented at entry levels, there is a clear underrepresentation of females at higher and mid-level roles. Implement hiring and promotion initiatives to increase diversity at these levels.

4. **Focus on Underperforming Departments:** Targeted approach to professional development, resource allocation, and clear performance goals in all departments to help boost productivity and performance scores.

5. **Equitable Performance Review Practices:**  The significant "Uneven – Men Benefit" ratings in **Sales & Marketing** raise concerns about potential gender bias in performance reviews. Review and update PRA processes to ensure fairness and equity across all departments, focusing on minimizing bias in performance evaluations.


