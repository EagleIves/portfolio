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
• Revolutionised commercial reporting by developing real-time Power BI dashboards, enabling data-driven decisions across leadership teams.   
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







</div>






