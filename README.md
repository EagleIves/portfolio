<img width="1879" height="147" alt="image" src="https://github.com/user-attachments/assets/48a49cae-6726-40a2-b5db-74a7e3b42764" /><div style="text-align: justify; text-justify: inter-word;">

# HELLO, I'M IVY KARANJA
Your partner in turning raw data into impactful insights. SQL, Power BI, Python, and Advanced Excel are my weapons of choice. Let's get cooking!


## WHO AM I?
My penchant for making connections and predicting outcomes based on historical events led me to Data Analysis. Now, with an in-depth understanding of business processes borne of years of experience working in a large corporation, I have graduated to the ranks of Business Analysis. I am your go-to girl for translating complex technical concepts to the customer-facing commercial teams and conversely, communicating core and niche business needs to technical teams. I use data analysis tools, automation tools, and AI to help businesses mine the gold hiding within their own data and therefore defy their past performance ceilings. Join me on this data adventure!


## EDUCATION
• Data Science and Machine Learning – MIT Institute for Data Systems and Society (Feb 2023)   
• Data Protection Course – CIPIT, Strathmore University (Apr 2024)   
• Certificate in Data Science, Strathmore University (2022)   
• BBS Financial Engineering, Strathmore University (2019)  
• Advanced Microsoft Excel – Corporate Staffing Services (2019)   
• Data Analytics on Python – Takenmind Global (2019)   



## WORK EXPERIENCE

### Business Analyst @ Simba Corporation (March 2022 - Present)
• Revolutionised commercial reporting by developing real-time Power BI dashboards, enabling data-driven decisions across leadership teams.   
• Created predictive algorithms for service date reminders, boosting service sales by 3%.   
• Implemented a Work in Progress tracking system and dashboard that created first-time visibility of aged service orders in the workshop, thereby improving closure rates by 8%.   


### Data Protection Officer @ Simba Corporation (October 2024 - Present)
• Formed a Data Management Committee to champion data protection practices across departments.   
• Designed and implemented staff training programs on data privacy and compliance.   
• Developed company-wide data governance policies to standardise information management.   


### Data Analyst ~ Self-Employed (August 2021 - February 2022)
• Created automated financial dashboards in Excel using advanced formulas and data analysis tool packs.
• Conducted statistical analyses using SPSS for client surveys and reports.
• Delivered client presentations that turned analytical findings into actionable recommendations.


## PROJECTS
### <ins>PROJECT 1: Customer Segmentation and Purchase Behaviour Prediction (Python) <ins>
#### OBJECTIVE
My goal was to classify and segment customers based on their historical purchases and ultimately accurately develop a model for predicting their future purchasing behaviour. I wanted the data to tell me where this American shopowner should put their money to get the most out of their investment.

#### CHAPTER 1: DATA TRANSFORMATION
Categorical variables such as "Season" and "Payment Method" are converted to a numerical format for clustering. Machine learning models work better with numerical inputs, so I needed to encode these categories as numbers.

Using One-hot encoding, I converted the "Payment Method" column into binary columns (0/1) for model compatibility. This helps the model detect patterns like "Cluster 0 prefers Credit Card payments."

#### CHAPTER 2: FEATURE SELECTION FOR CLUSTERING
Next, I identified cluster features that collectively define customer behaviour in the below categories. This ensures clustering is based on meaningful behavioral traits rather than irrelevant columns (e.g., *Customer ID*).

  **Demographics:** *Age*   
  **Spending habits:** *Purchase Amount, Monetary, High_Spender*   
  **Engagement:** *Frequency, Recency, Loyal_Customer, Frequent_Buyer*   
  **Preferences:** *Discount_Lover, Promo_User*

#### CHAPTER 3: CLUSTERING 
I utilised the Elbow/silhouette methods to ensure the selection of optimal clusters. This avoids oversegmentation resulting from the arbitrary choice of __*k*__. Optimal number of clusters identified was __Four(4)__.

<img width="700" height="500" alt="cluster_evaluation" src="https://github.com/user-attachments/assets/15108341-9227-46d5-93de-4c49be3025ec" />

I then grouped the customers by behaviour (spending, loyalty, etc.) using K-means clustering; a simple, efficient algorithm for partitioning data into __*k*__ clusters. I did this in Python by using the *fit_predict()* function, which assigns each customer to a cluster based on scaled features.

Next, I analysed cluster profiles to understand what defines each cluster (e.g., "Cluster 0 has high Purchase Amount and Loyal_Customer"). I did this by computing mean values per cluster to generate actionable insights such as "Target Cluster 0 with loyalty programs".

<img width="640" height="480" alt="cluster_characteristics" src="https://github.com/user-attachments/assets/6705e266-5c65-491a-bf83-38a7c9d118b2" />


__Customer Segments Identified:__

__1. Cluster 0: High-Value Loyal Customers__   
• Characteristics: High purchase amounts, frequent purchases, loyal  
• Top Purchases: Coat, Jacket, Dress   
• Recommendations: Premium outerwear, bundled accessories

__2. Cluster 1: Budget-Conscious Shoppers__   
• Characteristics: Lower spending, frequent discount/promo use   
• Top Purchases: T-shirt, Pants, Sneakers    
• Recommendations: Discounted bundles, seasonal promotions    

__3. Cluster 2: Occasional Luxury Buyers__   
• Characteristics: High spending but less frequent purchases   
• Top Purchases: Jewellery, Handbag, Sunglasses   
• Recommendations: Limited edition items, gift bundles   

__4. Cluster 3: Frequent Essentials Buyers__    
• Characteristics: Moderate spending, very frequent purchases   
• Top Purchases: Shirt, Blouse, Sweater   
• Recommendations: Subscription models, bulk discounts   

#### CHAPTER 4: ASSOCIATION RULES MINING

To find frequently co-purchased items, I employed the Apriori Algorithm, a model often used to discover relationships and dependencies between items in large transactional datasets. I used the following metrics within the algorithm in Python:   
__Support:__ How frequently itemset appears (min 5% here).   
__Lift:__ Measures dependence (lift > 1.2 means likely together).   
__Confidence:__ Probability of buying Y given X (min 50% here).   

The algorithm yielded a few association rule highlights as below:   
• Customers who buy Coats often buy Gloves (lift 1.8)   
• Handbag purchases are frequently paired with jewellery (lift 1.7)   
• Pants purchases often lead to Shirt purchases (lift 1.5)   

#### CHAPTER 5: CLUSTER-SPECIFIC RECOMMENDATIONS

To generate cluster-specific recommendations, I sought to define the top purchased items and filter association rules where antecedents match those items, for each cluster. The desired outcome was to get suggestions from the model, such as "If Cluster 0 buys Coats, recommend Gloves (from association rules)". These insights can then be used for targeted marketing.

__Marketing Strategy Recommendations:__

__1. For High-Value Customers (Cluster 0):__   
• Target with premium product launches   
• Offer exclusive early access to new collections   
• Bundle complementary high-margin items   

__2. For Budget Shoppers (Cluster 1):__   
• Highlight discount opportunities   
• Create value bundles of basic items   
• Promote seasonal clearance sales   

__3. For Luxury Buyers (Cluster 2):__   
• Focus on gift-oriented marketing   
• Highlight quality and exclusivity   
• Offer personalised shopping experiences   

__4. For Frequent Buyers (Cluster 3):__   
• Implement subscription or loyalty programs   
• Offer replenishment reminders for essentials   
• Provide volume discounts   


#### CONCLUSION
In this coding journey, customer secrets for this clothing store have been revealed. Now Mr Proprietor knows exactly how to target his customers and have them buying things they never would before, all because of a bit of analysis. Don't you just love data?!


### <ins>PROJECT 2: HR Analytics (Power BI) <ins>

### Objective   
The Objective was to create an HR analysis dashboard in Power BI, where HR officers can gain quick insights into a wide array of staff statistics, including headcount, leave utilisation, employee turnover, time and attendance, and more. Imagine a one-stop shop that answers all your staff-related questions. The dashboard aims to empower decision-makers with actionable information for effective workforce management, retention, succession planning, and overall employee satisfaction.

### Overview Page      
The Overview page of the report acts as a brief preview of the details to be revealed in the subsequent report pages. This is especially useful for upper management consumption, as it allows them to gain a high-level understanding of their workforce.
The Overview page touches on headcount, staff movement, demographics, leave statistics, location and the makeup of staff.

<img width="870" height="489" alt="image" src="https://github.com/user-attachments/assets/09e6613b-673a-4abe-a0a9-bfc1e5a83490" />   

### Headcount & Diversity      
The Headcount & Diversity page delves deeper into the defining characteristics of the workforce, illuminating key details such as the gender makeup, the percentage of the workforce that is unionised, the average tenure of employees and the period to retirement for older workers. These statistics may be drilled down further to filters of Division, Department, Functional Unit, Cadre, Job Category, Location and even Date of Joining the company.   
Notably, the workforce is mostly made up of men. This may lead to an important discussion on women's empowerment and the working environment in the Buffalo corporation. The majority of staff fall in the category of tenures at Buffalo of less than 5 years; this may prompt a discussion on the high turnover rate and measures that may be taken to improve employee satisfaction. 

<img width="874" height="490" alt="image" src="https://github.com/user-attachments/assets/5d25113d-b452-4f4c-90f6-d5758c4b8758" />   

### Annual Leave Summary    
Created Key Performance Indicators for leave liability, leave utilisation rate and end-of-year leave balance target. KPIs were calculated on a prorated basis; this means that leave statistics may be viewed up to the period under review, and not purely with a view to leave days entitled for the whole year. The slicers available allow for a deeper dive per division, department, location, etc.   

__*Key Insights:*__   
•	Leave utilisation rate steadily increases as the year wears on, whereas the prorated average leave liability per employee remains stable, even increasing at times. This indicates that while most employees utilise their allotted leave days as expected, there are a select few who utilise few to none, and thereby inflate the average leave liability.   
•	The specific individuals contributing to the unchanging average leave liability may be identified and subsequently followed up on in the table dubbed “Prorated Leave Balances by Name”. Simply selecting the Prorated Balance column label will sort the names in either ascending or descending order.   
•	By September 2025, the prorated leave utilisation rate was at 47% while the end-year target is 75%. With only 3 months left until December, urgent action must be taken by the HR department to minimise potential leave liabilities payable.   

<img width="876" height="491" alt="image" src="https://github.com/user-attachments/assets/bbeec9cb-57fb-453c-8394-d3920c781bd3" />   

### Staff Movement Summary   
A turnover analysis led to the development of KPIs such as the number of new entrants, exits, internal hires, average tenure of active employees and average tenure of inactive employees. I also established the distribution of reasons for exits over the last couple of years and the designation of exited employees. A trend analysis revealed fluctuations in entries and exits of staff, with exits doubling the number of entrants. This may point to a company strategy to reduce labour.   

<img width="876" height="489" alt="image" src="https://github.com/user-attachments/assets/2876dadc-32c9-481c-b6b5-cba725b266e4" />

### Time & Attendance   
The Time & Attendance page seeks to track the attendance habits of staff who work full-time from the office. Created KPIs for average time-in, average time-out, average work hours, attendance rate and standard workdays. All KPIs are dependent on the shift in question. The shift must be selected for the cards to reveal values; otherwise, the meaning would be distorted if calculated across several shifts.    
Additional considerations were made to ensure the accuracy of the report, namely: Approved leave days and applied leave days awaiting approval. This analysis required the integration of the attendance dataset with the leave dataset and, therefore, the setting up of necessary relationships between the two.    
The attendance rates were displayed by department to quickly pick out compliant and non-compliant employees. The departments may be expanded to include the individual employees in the visual by selecting the plus signs to the left of the department names.

<img width="876" height="492" alt="image" src="https://github.com/user-attachments/assets/27ba4a16-6c4d-40dc-ab15-a949e589fcaa" />    

### Goal Setting Status   
This page was created to track the progress of the performance appraisal process throughout the company as conducted within the Human Resource Management System (HRM). The same may also be utilised by department heads to ensure the completion of the exercise by their teams by employing row-level security so that they are only able to see their department’s statistics.

__*Key Insights:*__  
•	Of the 556 staff members employed by Buffalo Corporation, only 478 were enrolled to be appraised within the HRM, while 78 were exempted.   
•	At the individual self-evaluation level, 91% of staff had submitted their evaluation.   
•	90% of supervisors had submitted the evaluations of their subordinates, while 87% of reviewers had submitted their evaluations.   
•	Overall, 91% of the performance appraisal exercise was completed.   

<img width="872" height="489" alt="image" src="https://github.com/user-attachments/assets/b4e2a1d7-a8c4-411d-b2a1-28c50961650e" />

### End-of-Year Goal Review Evaluation    
To analyse how well employees have achieved the goals they set at the beginning of the year, the End-of-Year Goal Review Evaluation page was created.   

The analysis revealed that, on average, all employees rated themselves and their subordinates between 2 and 4, with most employees falling at the midpoint of 3. A deeper dive by department highlights high-performing and underperforming departments.   

Filtering by division showed that the Motors division skewed towards lower ratings of 2 and 3, while the Hospitality division gave higher ratings of 3 and 4.   

<img width="876" height="493" alt="image" src="https://github.com/user-attachments/assets/0acf13c3-44ab-4903-a802-8877df13599d" />

<img width="430" height="300" alt="image" src="https://github.com/user-attachments/assets/8bc8c451-008a-4888-888a-c4876bdc0fc9" /> <img width="430" height="300" alt="image" src="https://github.com/user-attachments/assets/9cb616de-a475-4721-a617-583023f2bc6a" />    
 

### <ins>PROJECT 3: Dynamic Work Organiser (Excel & VBA) <ins>

### What is it?   

Here we have a simple to do list tracker and dashboard. Have a view of what tasks are still pending, who’s responsible and the deadlines that are coming due.   

This document utilizes several advanced excel tools and features namely: visual basic macros, dynamic named ranges, conditional formatting, sheet navigation buttons among others. Update your list of completed tasks with the click of a button and see your progress.   

__SEE HOW IT WORKS!__

### Features & Tools

__1. INTERFACE__

• The Interface of the Work Organizer summarizes all tasks according to their deadline and current status.    
• It also provides for page navigation buttons to the full To Do List, the Completed Tasks and all existing standardized list entries.    
• This page automatically updates overtime and to reflect any changing work statuses.   

<img width="894" height="428" alt="image" src="https://github.com/user-attachments/assets/348fffa7-b0b5-4181-9a23-1506c03a8e59" />    

__2. TO DO LIST__   

• The second page of the Organizer details all the ongoing workstreams and tasks to be completed.   
• Tasks due this week are highlighted amber while overdue tasks are highlighted in red to alert the responsible persons.   
• Tasks marked as complete are copied in the “Completed” sheet to archive them.   

<img width="894" height="431" alt="image" src="https://github.com/user-attachments/assets/ebc13527-ccbc-44a4-80e6-90b0b61ed2ad" />   

__3. COMPLETED LIST__    

• As earlier stated, Tasks marked as complete are copied in the “Completed” sheet to archive them.    
• This is an automatic process that is triggered by changing the status of a task from “In progress” to “Completed”.   
• There is also a Sort button that arranges the tasks in ascending order depending on their stated deadline.    

<img width="987" height="151" alt="image" src="https://github.com/user-attachments/assets/bc79e4bd-3894-4615-8d95-2dfc373568c9" />

__4. LISTS PAGE__   

• The last page hosts some of the named ranges and data validation lists for any necessary amendments.   
• Any additions to the list are automatically added to the saved named ranges and data validation lists   

<img width="918" height="422" alt="image" src="https://github.com/user-attachments/assets/f8996626-dad8-4eb4-863b-4750b8b641e2" />







</div>






