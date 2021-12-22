# Django-eCommerce-v2
From [Very Academy](https://www.youtube.com/watch?v=EbLEyM9SyZQ&list=PLOLrQ9Pn6cay_cQkyg-WYYiJ_EKU8KWKh)
To be used as a playground for some Django 4.0 features.

Project Brief:
1. Online Store capabilities selling various merchandise
1. Customer interaction: product comments / reviews
1. Website keyword search form with robust search and filter functionality
1. Live Chat help desk
1. Customer coupon system
1. Customer Portal

## Database Tables Design
- User
- Product
- Reviews
- Helpdesk
- Comments
- ....

### Mission Statement
The purpose of the inventory app database is to maintain the data that is needed to support online retail sales and stock inventory management.

### Mission Objectives
1. Maintain information on multiple types of products
1. Keep track of stock levels

### Other Aspects
1. What needs to appear on the website?
1. What do customers need to know about a product?
1. What data is needed to record stock level/managemement?

### Preliminary Field List
- Name
- Description
- SKU
- Type
- Image
- Color
- Size
- Brand
- Weight
- Category
- RR_Price
- Stock_Price
- Sale_Price
- Stock_Qty

### Establishing Table Structures
We start this process by:
1. Analyzing preliminary field list
1. Using collected data
1. Using mission objectives

A field is a characteristic of the subject. A name is a characteristic of the product. Same as description SKU etc.
So our Table is Product.

Looking at collected data you can identify a particular subject. 

Looking at mission objectives we can see we need a User Table.

