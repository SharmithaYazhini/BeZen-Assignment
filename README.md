# BeZen-Assignment
# Description 
Attached is a CSV file which has the following details about products from various ecommerce sites. 

● UUID (Primary Key) 

● Price (String) 

● Price_unfiltered (String) 

● Product Type 

● Category 

● Level 1 -> This is just a classification of a product. 

CSV FILE -> DOWNLOAD 

# Task: Use the database to find the following results from this data. 

## 1. Products without prices 
  1. Identify the price column 
  
  2. Use the isna() command
  
  ![image](https://user-images.githubusercontent.com/104150250/172045443-a83ea761-1cd6-47ae-b3a3-f3b193f58e1b.png)


  
  3. Print the products without price
 
  ![image](https://user-images.githubusercontent.com/104150250/172045384-eeb3c03b-d53f-4539-89b7-b07c60f196f5.png)

## 2. Count of products without prices and with prices in each Product Type, Category, Level 1 
  
  1. In products withot price:
  ![image](https://user-images.githubusercontent.com/104150250/172045499-1a30b360-3029-4d13-a8c4-21be35367dc1.png)
  
  2. Count the unique products
  ![image](https://user-images.githubusercontent.com/104150250/172045530-8cca9b5e-c178-4a2d-bdf2-7fe0ce16c9ec.png)
  
  3. Count the unique category
  ![image](https://user-images.githubusercontent.com/104150250/172045555-d672e057-a42d-4549-9efb-fd32619e7d74.png)
  
  4. Count the unique Level 1
  ![image](https://user-images.githubusercontent.com/104150250/172045572-13017d93-3d04-4159-9986-a61231cda7ee.png)
  
  ![image](https://user-images.githubusercontent.com/104150250/172045647-0dfdda87-f9e7-4a11-99dc-48aabab4506b.png)

## 3. Correct Product Prices in the correct format (eg: $56) wherever possible and separate them into currency and value columns. 
  
  1.Replce $ with ""
  ![image](https://user-images.githubusercontent.com/104150250/172045661-8f16e151-bcdd-4856-93d3-d6d61fc317f3.png)
  
  2.Edit the price string as $ + Value
  
  3.Use separete columns for Currency type and value

## 4. List out the categories with average price of product. 
  1.Use the numpy function to calculate the mean and group by category
  ![image](https://user-images.githubusercontent.com/104150250/172045700-506ec27f-9d0b-46c0-939a-eb2a40d7c361.png)

  
REQUIREMENTS:
GOOGLE COLAB
