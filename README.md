# **BigMart-Store-Sales-Prediction-End-to-End-Pipeline**

![image](https://user-images.githubusercontent.com/127007794/230469624-fc7ae7ae-031c-4de5-b714-7ad69853825f.png)

## **Problem Statement**

Nowadays, shopping malls and Marts keep track of individual item sales data in order to forecast future client demand and
adjust inventory management. In a data warehouse, these data stores hold a significant amount of consumer information and particular item details. By mining the data store from the data
warehouse, more anomalies and common patterns can be discovered.

## **Data*

Item_Identifier: Unique product ID
Item_Weight: Weight of product
Item_Fat_Content: Whether the product is low fat or not
Item_Visibility: The % of total display area of all products in a store allocated to the
Item_Type: The category to which the product belongs
Item_MRP: Maximum Retail Price (list price) of the product
Outlet_Identifier: Unique store ID
Outlet_Establishment_Year: The year in which store was established
Outlet_Size: The size of the store in terms of ground area covered
Outlet_Location_Type: The type of city in which the store is located
Outlet_Type: Whether the outlet is just a grocery store or some sort of supermarket
Item_Outlet_Sales: Sales of the product in the particular store. 

This is the outcome 25 lacs total Dataset. (2.5 Million records)
particular product variable to be predicted

## **Project Architecture**

<img width="647" alt="image" src="https://user-images.githubusercontent.com/127007794/230469199-942185e9-2e5f-4787-873a-c36053b7f3d0.png">

## **How to Run**

Create new env using below command:
conda create -n env_name python==3.6.9
Activate your envirnment
conda activate env_name
Install requriments.txt file
Create MongoDB Database
Add your mongodb code under logger file & dbOperation file
Run your app.py file name
python app.py
Enter your values and predict the single prediction




