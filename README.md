# 📦 Predictive Analytics: Classifying Delivery Timeliness in Supply Chain
*A Classification Model for Assessing Delivery Timeliness*  

## 🚀 Project Overview  
This project applies **predictive analytics** to optimize supply chain management by identifying patterns and predicting late deliveries.  
We explored payment methods, regional sales trends, customer segments, and delivery statuses, and built classification models to assess **delivery timeliness**.  

## 🎯 Objectives  
- Analyze supply chain data to extract actionable insights  
- Model late delivery risk using classification techniques  
- Identify high-risk product categories, markets, and regions  
- Recommend strategies to reduce late deliveries and improve customer satisfaction  

## 🛠 Tech Stack  
- **Language**: R ![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)  
- **Notebook & Reporting**: RMarkdown, knitr, Pandoc  
- **Libraries**: `ggplot2`, `dplyr`, `caret`, `class`, `e1071`  
- **Modeling**: Logistic Regression, Naive Bayes, K-Nearest Neighbors (KNN)  
- **Visualization**: Bar plots, heatmaps, comparative charts  
- **Tools**: RStudio, PowerPoint  

## 📊 Exploratory Data Analysis (EDA)  
- **Payment Trends**: Debit cards were most common; cash usage declining  
- **Sales Insights**: Europe led in sales; outdoor & fitness products dominated  
- **Loss Analysis**: Clothing & footwear had the highest loss rates  
- **Customer Segments**: Consumer segment dominated over Corporate and Home Office  
- **Delivery Status**: Late deliveries were the most frequent, followed by early shipments  

## 🤖 Model Building & Performance  

| Model                  | Accuracy | Recall  | F1 Score | Notes                                  |
|-------------------------|----------|---------|----------|----------------------------------------|
| Logistic Regression     | **98.89%** | **100%** | **99.44%** | Best performing, highly reliable        |
| Naive Bayes             | 55.24%   | 99.97%  | 71.16%   | High recall, many false positives       |
| K-Nearest Neighbors     | 84.93%   | 86.04%  | 85.48%   | Balanced but less accurate than Logistic Regression |

**Winner**: ✅ Logistic Regression — superior precision, recall, and overall accuracy  

## 📈 Key Insights  
- Late deliveries are **common** → process improvement needed  
- Logistic Regression is a strong candidate for deployment  
- Payment method & product category are strong predictors of delivery risk  

## 👥 Team  
- Yash Doshi
- Nemi Makadia  
- Aneri Patel  
- Nihar Domala  

## 📝 Conclusion  
This project demonstrates the value of **predictive modeling** in supply chain management.  
By deploying classification models, businesses can:  
- Reduce delivery risks  
- Improve operational efficiency  
- Strengthen customer satisfaction  

