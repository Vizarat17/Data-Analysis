This project offers a comprehensive marketing analytics solution for ShopEasy, an online retail brand facing challenges in customer engagement and conversion rates. The objective was to uncover key insights by analyzing customer behavior, product feedback, and campaign effectiveness using a blend of SQL, Python, and Power BI.

The foundation of the analysis began with building a robust data model using SQL scripts to define dim_customers, dim_products, and fact tables for customer_reviews and engagement_data. This structure allowed for efficient analysis of marketing performance and customer interactions across multiple dimensions.

To enhance the depth of analysis, customer review data was enriched using Python. The nltk library's VADER sentiment analysis tool was used to evaluate the emotional tone of each review. These scores were then categorized into sentiment groups—Positive, Negative, Mixed, and Neutral—by blending the sentiment score with the review rating. This enriched dataset provided deeper insight into how customers felt about various products and services.

The analysis culminated in a Power BI dashboard, which visualizes key metrics such as monthly conversion rates, customer engagement across different content types, and sentiment distribution. A custom calendar table built using DAX enables dynamic filtering and seasonal analysis.

Key findings included:

Conversion rates showed sharp month-to-month variation, with strong performance in January and weak results in May.

Engagement declined steadily over the year, especially in views and interactions on social media content.

Most customer feedback was positive, though mixed reviews revealed opportunities for product and service improvements.

The final presentation ties all insights into a strategic action plan, focusing on improving underperforming campaigns, enhancing content engagement, and addressing customer concerns.

This project demonstrates how integrating data modeling, natural language processing, and business intelligence tools can help businesses make informed, customer-focused decisions.

