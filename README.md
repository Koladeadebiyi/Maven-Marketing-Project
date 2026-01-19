# **Maven Marketing Project**  

## **Project Background**  

The Maven Marketing Project analyzes web purchase behaviors, marketing campaign performance, and product sales to derive insights that enhance business decision-making. This analysis is based on a dataset that includes customer demographics, income range, marital status, purchasing behaviors, and sales performance.  

The primary goal is to identify trends, underperforming areas, and opportunities for optimization in marketing strategies. Additionally, the project incorporates data from **2,240 customers** of Maven Marketing, covering customer profiles, product preferences, campaign effectiveness, and channel performance.  

## **Recommended Analysis**  

Are there any missing values or outliers in the dataset? How should they be handled?

What factors significantly impact the number of web purchases?

Which marketing campaign was the most successful?

What does the average customer look like?

Which products perform best?

Which channels are underperforming?

<img width="989" height="558" alt="image" src="https://github.com/user-attachments/assets/616390a3-0a3f-4d6f-bac9-cf3dedb28f69" />


## **Insights Deep Dive**  


**Identifying Missing Values and Outliers**

Upon reviewing the dataset, the Income column contained several null entries, making it necessary to clean the data before meaningful analysis could proceed. These records were removed using Power Query’s Remove Blank Rows feature to maintain the accuracy of insights.

Handling the Outlier (666,666 in Income Column)

During exploratory data analysis, an income value of 666,666 stood out far above the rest of the data, which typically ranged from 2,000 to 165,000. To prevent skewing statistical results, this outlier was replaced with the median income of the dataset.

### **Web Purchase Analysis**  

 **Income Range**  
- Customers earning **50k-100k** make the most web purchases.  
- Very few purchases come from income ranges below **20k** and above **200k**.  
- This suggests that **middle-income consumers are the most active online buyers**.  

**Age Group**  
- The highest number of web purchases comes from individuals born between **1960-1980**, followed by **1950-1960**.  
- **Younger groups (1980-2000)** also contribute, but at a lower rate.  
- **Older generations (1893-1940)** have the least web purchases.  
- This implies that **middle-aged consumers drive the majority of online purchases**.  

 **Marital Status**  
- **Married and courting** individuals make the most purchases.  
- **Single and divorced** individuals buy less.  
- **Widowed and YOLO categories** have minimal engagement.  
- This indicates that **family-oriented individuals tend to have higher purchasing power**.  

**Education Level**  
- Customers with a **Graduation or PhD** education level purchase the most.  
- **Master’s and 2nd Cycle degree holders** also contribute significantly.  
- Customers with **Basic education** have the least web purchases.  
- This suggests that **higher education correlates with increased online shopping activity**.  

**Country**  
- **Spain** has the highest number of web purchases, followed by **Saudi Arabia** and **Canada**.  
- **Mexico, Germany, and the USA** have the lowest web purchase rates.  
- This indicates that **geographic location influences online buying behavior**.  

### **Marketing Campaign Performance**  
The most successful marketing campaign was:  
- **Campaign 4** with **25.04% success rate**.  
- **Campaign 3 and Campaign 5** followed closely, each with **24.44% success rate**.  

This suggests that **Campaign 4 was the most effective in driving customer engagement and purchases**.  

### **Customer Profile Analysis**  
The **average Maven Marketing customer** is:  
- **Married**  
- Born between **1960-1980**  
- Earns an income of **50k-100k**  
- Has a **Graduation degree**  
- Lives in **Spain**  
- Primarily purchases **wine from the store**  

### **Product Performance**  
The **top-performing products** are:  
- **Wine** – **50.17% of total sales**  
- **Meat** – **27.56% of total sales**  

These products drive the highest revenue, making them key contributors to business success.  

### **Channel Performance**  
- The most underperforming sales channel is **Deal (15.64%)**.  
- The highest-performing sales channel is **Store (38.96%)**.  

This indicates that **online and deal-based sales strategies need improvement**, while in-store purchases remain strong.  

## **Recommendations**  

### **1. Enhance Marketing Strategies for Middle-Income and Middle-Aged Consumers**  
- Since **50k-100k earners** and **1960-1980 age groups** are the most active buyers, marketing campaigns should target this segment with personalized offers and loyalty programs.  
- Email marketing and digital ads should highlight products that appeal to this demographic.  

### **2. Optimize Product Offerings**  
- **Wine and meat** are top-performing products, suggesting an opportunity for bundling these items in promotions.  
- Inventory management should prioritize these products, ensuring consistent availability and seasonal discounts.  

### **3. Improve Campaign Strategies**  
- **Campaign 4 was the most successful**, meaning its tactics should be analyzed and replicated across future campaigns.  
- Campaigns 3 and 5 also performed well, indicating a need to refine their strategies for even better engagement.  

### **4. Strengthen Underperforming Sales Channels**  
- **Deal-based promotions** need a revamp. Offering time-sensitive discounts and flash sales can boost engagement.  
- Online sales should be optimized by enhancing user experience on the website and improving checkout processes.  

### **5. Target Geographic Expansion**  
- Since **Spain, Saudi Arabia, and Canada** lead in web purchases, marketing efforts should be focused on these regions.  
- Tailored promotions and localized content should be developed for these high-performing markets.  
- **Mexico, Germany, and the USA** should be analyzed further to identify barriers to online sales and potential strategies for improvement.  

### **6. Refine Customer Retention Strategies**  
- Since **married and highly educated individuals** purchase the most, loyalty programs, exclusive discounts, and referral bonuses should target this audience.  
- Personalized recommendations based on past purchases can increase repeat purchases.  

 **Conclusion**  
This analysis provides critical insights into customer purchasing behavior, campaign effectiveness, and product/channel performance. By leveraging these findings, Maven Marketing can **optimize its marketing strategies, enhance customer targeting, and improve overall sales performance**.  
