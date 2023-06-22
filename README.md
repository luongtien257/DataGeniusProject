# Data Genius Project
## 1. Objective
* Crawl product data from Tiki e-commerce website (https://tiki.vn/). At least **2 sub-categories or 5000 products.**
* Perform EDA on the collected datasets.
* Build Machine Learning model for **prediction, categorization, and clustering tasks.**
## 2. Tiki_Crawler
I used Python *requests* library to access the Tiki's public API, following this video [1].Since no specific category was required, I decided to **crawl all 14467 products in the *Sách kinh tế* (economy book) category**. My main code modifications here are:
* Use stack structure to get all sub-categories of the input category in *crawl_product_id.py.* Then query all the product-id in each sub-category.
* Modify the *parser_product* function to get the essential parameters in each product. Then export the .csv file for every 1000 collected product records.
## 3. EDA Process
* Data cleaning: The detail cleanlog is written in the *EDA.ipynb* file. After the cleaning step, the data size reduced to 14399 product-id.
* Analyze the dataset based on 4 criteria: **Quantity distribution, Correlation between quantities, Category Comparison, Repeated Words and Best Seller**
* Use mainly the *plotly* library to create interactive visualizations. 
## 4. Machine Learning models
## 5. References
1. https://youtu.be/4ANrdE3FDPw'
