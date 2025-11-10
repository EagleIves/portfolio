<div style="text-align: justify; text-justify: inter-word;">

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
• Revolutionized commercial reporting by developing real-time Power BI dashboards, enabling data-driven decisions across leadership teams.   
• Created predictive algorithms for service date reminders, boosting service sales by 3%.   
• Implemented a Work in Progress tracking system and dashboard that created first-time visibility of aged service orders in the workshop, thereby improving closure rates by 8%.   


### Data Protection Officer @ Simba Corporation (October 2024 - Present)
• Formed a Data Management Committee to champion data protection practices across departments.   
• Designed and implemented staff training programs on data privacy and compliance.   
• Developed company-wide data governance policies to standardize information management.   


### Data Analyst ~ Self-Employed (August 2021 - February 2022)
• Created automated financial dashboards in Excel using advanced formulas and data analysis tool packs.
• Conducted statistical analyses using SPSS for client surveys and reports.
• Delivered client presentations that turned analytical findings into actionable recommendations.


## PROJECTS
### PROJECT 1: Customer Segmentation and Purchase Behaviour Prediction
#### Objective
My goal was to classify and segment customers based on their historical purchases and ultimately accurately develop a model for predicting their future purchasing behaviour. I wanted the data to tell me where this American shopowner should put their money to get the most out of their investment.

#### Chapter 1: Data Transformation
Categorical variables such as "Season" and "Payment Method" are converted to a numerical format for clustering. Machine learning models work better with numerical inputs, so I needed to encode these categories as numbers.

Using One-hot encoding, I converted the "Payment Method" column into binary columns (0/1) for model compatibility. This helps the model detect patterns like "Cluster 0 prefers Credit Card payments."

#### Chapter 2: Feature Selection for Clustering
Next, I identified cluster features that collectively define customer behaviour in the below categories. This ensures clustering is based on meaningful behavioral traits rather than irrelevant columns (e.g., *Customer ID*).

  **Demographics:** *Age*   
  **Spending habits:** *Purchase Amount, Monetary, High_Spender*   
  **Engagement:** *Frequency, Recency, Loyal_Customer, Frequent_Buyer*   
  **Preferences:** *Discount_Lover, Promo_User*

#### Chapter 3: Clustering 
I utilized the Elbow/silhouette methods to ensure the selection of optimal clusters. This avoids oversegmentation resulting from the arbitrary choice of __*k*__. Optimal number of clusters identified was __Four(4)__.

<img width="700" height="500" alt="cluster_evaluation" src="https://github.com/user-attachments/assets/15108341-9227-46d5-93de-4c49be3025ec" />

I then grouped the customers by behavior (spending, loyalty, etc.) using K-means clustering; a simple, efficient algorithm for partitioning data into __*k*__ clusters. I did this in Python by using the *fit_predict()* function, which assigns each customer to a cluster based on scaled features.

Using Principal Component Analysis (PCA), I visualized the clusters generated in a 2D plot to establish any overlaps between clusters.
<img width="800" height="500" alt="customer_segments" src="https://github.com/user-attachments/assets/af359af2-25c1-4af2-a940-300fd541f7ca" />




</div>






