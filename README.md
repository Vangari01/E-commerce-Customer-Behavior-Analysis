# E-commerce-Customer-Behavior-Analysis
This project analyzes 1M+ e-commerce transactions to uncover customer behavior, revenue patterns, and product performance using Python, SQL, and data visualization.
Analyzed customer buying patterns across different demographics
Identified top-performing products based on ratings, orders, and revenue
Evaluated the impact of coupons and campaigns on customer spending
Compared purchasing behavior across shipping methods and time (weekend vs weekday)
Built an interactive dashboard for business decision-making
TOOLS USED
Jupyter Notebook for:
Exploratory Data Analysis (EDA):Inspected dataset using info(), describe(), checked missing values and duplicates
Data Cleaning: Handled missing values:return_reason → "No Return", coupon_code → "No Coupon",customer_feedback → "No Feedback"
               Converted data types:order_date → datetime, numerical columns to correct formats
Feature Engineering: Created new features:order_frequency → number of times an order ID appears  
                     Investigated duplicate order IDs
SQL ANALYSIS (PostgreSQL)  
Revenue by gender,Coupon usage vs spending behavior,  Top products with the highest review rating, Quality (rating),Popularity(orders), Business value(revenue),Shipping method vs average purchase, Campaign performance analysis,Customer segmentation,Top products per category (Window functions),Weekend vs weekday buying patterns,Revenue contribution by age group
Built an interactive dashboard using PowerBI: a. Total customers & average purchase value
                                              b. Revenue by product category
                                              c. Campaign source performance
                                              d. Gender distribution
                                              e. Age group vs revenue
                                              f. Sales trends & filter
Insights: a. Certain product categories contribute the highest revenue despite similar order volumes
          b. Customers using coupons often spend equal to or more than average purchase value
          c. Weekend and weekday buying patterns vary significantly across age groups
          d. Campaign sources impact both customer acquisition and revenue differently
          e. High-rated products do not always generate the highest revenue

