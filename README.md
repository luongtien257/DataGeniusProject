# DataGeniusProject
## 1. Objective
* Crawl product data from Tiki e-commerce website (https://tiki.vn/). At least **2 sub-categories or 5000 products.**
* Perform EDA on the collected datasets.
* Build Machine Learning model for **predictions, categorization, and clustering tasks.**
## 2. Tiki_Crawler
I used Python to access the Tiki's available API, following this video [1]. My main modifications here are:
* Use stack structure to get all sub-categories of the input category in *crawl_product_id.py.* Then query all the product-id in each sub-category.
* Modify the *parser_product* function to get the essential parameters in each product. Then export the .csv file for every 200 collected product records.
## 3. EDA Process
## 4. Machine Learning models
## 5. References
1. https://youtu.be/4ANrdE3FDPw'
