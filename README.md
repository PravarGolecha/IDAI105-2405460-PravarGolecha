### IDAI105-2405460-PravarGolecha

# Data Mining: Market Basket Analysis of Amazon by Customer Segmentation and Shopping Patterns

### Project Objectives:

The objective of this project is to analyze Amazon's e-commerce data to:
 Understand customer shopping behaviors through data analysis.
 Segment customers based on their purchasing patterns using clustering techniques.
 Identify relationships between products using Association Rule Mining.
 Analyze customer reviews to gain insights into sentiment and satisfaction levels.
 Develop an interactive dashboard using Streamlit for data-driven marketing strategies.

### Expected Outcomes

#### Customer Segmentation:
Clear identification of customer segments based on factors such as discounted price, actual price, product category, rating, and rating count.
Insights into different customer groups, such as budget-conscious buyers, premium shoppers, and frequent buyers.
Recommendations for personalized marketing campaigns and tailored promotions.

#### Frequent Itemset Identification:
Discovery of product associations using association rule mining (Apriori algorithm).
Identification of frequently bought-together items to enable better product bundling and cross-selling strategies.

#### User Behavior Analysis:
Understanding customer preferences based on product ratings, reviews, and buying frequency.
Insights into popular product categories and key factors influencing purchase decisions.
Sentiment analysis of customer reviews to assess brand perception and satisfaction levels.

#### Data Visualization and Interactive Insights:
Development of an interactive dashboard using Streamlit to present findings in a user-friendly manner.
Visualizations such as histograms, scatter plots, bar charts, and heatmaps to help interpret shopping trends.

#### Business Impact and Strategic Recommendations:
Improved customer targeting and segmentation for enhanced marketing efficiency.
Data-driven decisions for inventory management and sales optimization.
Enhanced customer experience and satisfaction by aligning product recommendations with shopping behaviors.

#### Interactive Streamlit Dashboard

Develop a user-friendly web app to visualize:
 Customer Segments
 Frequent Itemsets & Association Rules
 Customer Review Analysis & Sentiments
Enable Amazon’s business teams to explore real-time insights interactively.

###	Data Cleaning and Preprocessing
- **Removed missing values** from key columns like `product_id`, `actual_price`, `discounted_price`, `rating`, etc.  
- **Normalized numerical data** and **encoded categorical features**.  
- Ensured dataset consistency for analysis.

#### Sinpets of code:

![Screenshot 2025-03-06 125021](https://github.com/user-attachments/assets/94e49172-03eb-4962-87d2-c9dcfce6dcec)
![Screenshot 2025-03-06 125056](https://github.com/user-attachments/assets/9a576472-aa7b-4d1d-bf60-fe6277fd971c)


#### Below Link is for Dataset Cleaning code 
https://colab.research.google.com/drive/180K2tqA4n89lcheQxxBH6LUYgSceOFlr?usp=sharing

### EDA Analysis
- **Histograms & Box Plots** to analyze `actual_price` & `discounted_price`.  
- **Scatter Plots** to study relationships between `discount_percentage`, `actual_price`, and `discounted_price`.  
- **Bar Charts & Pie Charts** to explore product categories and most purchased items.  
- **Heatmaps** to visualize correlations between price, rating, and category. 

#### Sinpets of Analysis:
![Screenshot 2025-03-06 133333](https://github.com/user-attachments/assets/2a3e08fa-c89b-4eda-a23f-a47974920883)
![Screenshot 2025-03-06 133707](https://github.com/user-attachments/assets/8d351fec-e5d7-42b7-9b06-017fc7aa49ad)
![Screenshot 2025-03-06 133725](https://github.com/user-attachments/assets/78376e88-9c12-4c27-93c2-7a5b7b349480)
![Screenshot 2025-03-06 133928](https://github.com/user-attachments/assets/cb0d9f3f-8ff9-4380-a62e-f1b5539d841b)
![Screenshot 2025-03-06 133953](https://github.com/user-attachments/assets/3e9b7717-2273-460d-863e-9f1245a96863)
![Screenshot 2025-03-06 134014](https://github.com/user-attachments/assets/e1dad120-e881-49e6-9827-6c43950f5839)
![Screenshot 2025-03-06 134031](https://github.com/user-attachments/assets/63f59893-4ad8-4a20-a837-54d141ecab1a)
![Screenshot 2025-03-06 134055](https://github.com/user-attachments/assets/e4438218-edaa-42ed-b18b-a3877b76a231)
![Screenshot 2025-03-06 134127](https://github.com/user-attachments/assets/b565df2f-0107-49ff-81b2-98863522cb19)
![Screenshot 2025-03-06 134149](https://github.com/user-attachments/assets/261a34cb-9280-4822-a86d-46f475015a45)

#### Below Link is for EDA Analysis:
https://colab.research.google.com/drive/1GavFYexHwA1Qr0s45uag18rmPcqB8L6G?usp=sharing


###  Customer Segmentation 
- Applied **K-Means Clustering** to group customers based on:  
  - **Discounted Price**  
  - **Actual Price**  
  - **Product Category**  
  - **Ratings & Review Counts**  
- Used **Elbow Method** to determine the best number of clusters.  

#### Sinpets of Customer segregation and K-Means Clustering:
![Screenshot 2025-03-06 155041](https://github.com/user-attachments/assets/257d3c8b-180c-4282-a27e-f5e8ee2c25f5)
![Screenshot 2025-03-06 155101](https://github.com/user-attachments/assets/ca9a5a35-8a6f-450a-b3ae-e953f92279e1)
![Screenshot 2025-03-06 155131](https://github.com/user-attachments/assets/45b7c559-5fd9-48c8-b2ef-1f8d8fd52fcf)
![Screenshot 2025-03-06 155201](https://github.com/user-attachments/assets/c3920be8-0b8d-47d8-9992-fd9e180afcdd)

#### Below Link is for Customer segregation and K-Means Clustering:
https://colab.research.google.com/drive/1VfJKvocDUFxEaskvHPCfcr-Q8e5eRW_7?usp=sharing


### Association Mining Rules

- Applied **Apriori Algorithm** to discover product relationships using:  
  - `product_id`, `product_name`, `category`, `discounted_price`, `actual_price`  
- Identified **frequently purchased itemsets** using `support`, `confidence`, and `lift`.  
- Recommended **cross-selling & product bundling** strategies based on insights.
- As such there was no data for apriori algorithm so its file is mostly empty
  
#### Sinpets of Association Mining Rules:
![Screenshot 2025-03-06 172131](https://github.com/user-attachments/assets/389752ce-8a83-4e8b-914c-4ef7bb1c844b)
![Screenshot 2025-03-06 172147](https://github.com/user-attachments/assets/b895375d-e981-4338-a52c-1241aa7bd0bd)


#### Below Link is for Association Mining Rules:
https://colab.research.google.com/drive/1O0cRgQuvV-6cIptwZP3OqUVNVqZw_WuT?usp=sharing


### User Behavior Analysis**

- **Performed Sentiment Analysis** on customer reviews (`review_content`).  
- **Created Word Clouds** to visualize commonly used review words.  
- **Analyzed Rating Distribution** to see customer satisfaction trends.  
- **Identified Top Reviewers & Most Reviewed Products**. 


#### Sinpets of User Behavior Analysis:
![Screenshot 2025-03-06 203940](https://github.com/user-attachments/assets/ab45730e-6942-480c-b2aa-b7eeb637347e)
![Screenshot 2025-03-06 203954](https://github.com/user-attachments/assets/f8045a28-0c34-466b-8a72-24e25b674b98)
![Screenshot 2025-03-06 204011](https://github.com/user-attachments/assets/cb772e35-0b6c-4904-bebb-f5710ca3515c)
![Screenshot 2025-03-06 204030](https://github.com/user-attachments/assets/1b3b517f-0dd1-454c-b916-66c8e38eaccd)
![Screenshot 2025-03-06 204048](https://github.com/user-attachments/assets/89551ca1-fb8b-4453-a77e-de12a4f88dec)
![Screenshot 2025-03-06 204104](https://github.com/user-attachments/assets/3e0b6ab2-7f8b-4a29-8766-2497b74a4c88)
![Screenshot 2025-03-06 204216](https://github.com/user-attachments/assets/1daa6c58-dcbf-4030-b1a9-0c559cbacc4a)

#### Below Link is for User Behavior Analysis:
https://colab.research.google.com/drive/1VEuzVrz0lLz8UGJoDUngWMGEttymnowK?usp=sharing


## Streamlit Deployment

- **Developed an interactive Streamlit Dashboard** with:  
   Customer Segmentation Analysis  
   Association Rule Mining Insights  
   User Behavior Trends & Sentiment Analysis  
- **Deployed on Streamlit Cloud** for easy access.

#### Link for Streamlit Dashboard:
https://data-mining-sa-code-gwxceeyaunjwkcwsi7nvrx.streamlit.app/
