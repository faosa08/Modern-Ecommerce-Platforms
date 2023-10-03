# Modern-Ecommerce-Platforms
Design and Develop Modern Ecommerce Plaffor

# Project Overview

Website design for selling fresh, 100% pure Arabica coffee beans. We distribute roasted coffee. There will be 3 levels: light roast coffee, medium roast coffee, and dark roast coffee. We can be confident that our coffee is of excellent quality and premium. and have standards in production It is coffee grown using natural methods. Do not use chemicals in growing. and take care of every step of producing quality coffee By choosing to design a website that is simple to use and not complicated to facilitate customer access. The website is designed through WordPress, a website-making platform that is very popular in today's era because of its simplicity and many add-ons used for website development. The strengths that we choose to use WordPress are: easy to create a website, secure, and frequently upgraded. This is considered a strong point of the program because WordPress is a website creation platform that has system upgrades and the capabilities of the system often That will make our website work more efficiently. Can be used in a variety of ways than before. And it's more convenient than before if you want to edit your website and create websites in a variety of theme And WordPress Plugins have a variety and equipment to work with the website. If you change it again The website will change format.
And it can be done in many languages. WordPress is popular all over the world. This makes it possible to support multiple languages. There are also plugins created to support multilingual websites and to be able to do business with WordPress Can be made and sold to various users You can create work and market with WordPress yourself by making themes and plugins that are worth sending to the market continuously.

### Software used

**Laragon** The reason to use laragon is that it is a web server emulator. Laragon is fast and efficient for PHP, Node.js, Python, Java, Go, Ruby. It is fast, lightweight, easy to use, and easily extensible. Especially for building and managing modern web applications. Focus on efficiency Designed with stability in mind Simplicity, flexibility and freedom, so you'll find Laragon works quickly and smoothly.

**Wordpress** At its core, WordPress is the simplest, most popular way to create your own website or blog. In fact, WordPress powers over 43.3% of all the websites on the Internet. Yes – more than one in four websites that you visit are likely powered by WordPress. What Is WordPress? Explained for Beginners

**Visual Paradigm** is a leading and globally recognized provider for Business and IT Transformation software solutions. It enables organizations to improve business and IT agility and foster innovation through popular open standards. Our award-winning products are trusted by over 320,000 users in companies ranging from small business, consultants, to blue chip organizations, universities and government units across the globe. About Visual Paradigm Visual Paradigm.

### Method
After we have successfully logged in, it will bring up Wordpress for us. There won't be much there. Everything we want to do or want we have to download ourselves. Download it within Wordpress. The first thing we need to do is our website page. in making website pages We have two paths to choose from. First, design it yourself. Second, find other people's themes and change them into your website page. I chose to find someone else's theme to use, which I chose the theme of Coffee Block version 1.0 By SKT Themes.
his website page. His theme will be selling coffee beans and giving knowledge about coffee. which is very similar to my concept. So I have chosen our theme to change to my website for selling coffee beans. We have chosen the theme and the next step is to decorate our website page. How do you want it to be? Whatever you want, we can do as we want. We've finished decorating everything. Next, we'll add a plugin. First, we have to explain what a plugin is. A plugin is an add-on to WordPress in the form of a script that will help increase efficiency. and expand the ability to make ordinary websites It has become a complete website. More suitable for use in each purpose. 

#### What plug-ins do you use?
- **Woocommerce**
What is Woocommerce and what are its advantages?
It is a plugin that can turn a simple WordPress website into an e-commerce website in just a few clicks. With a variety of abilities Sell many types of products Whether it is an ordinary product that can be tangible Digital file type products.
WooCommerce can do everything a basic e-commerce website should have, such as a membership system, payments, shipping, warehouse management, and sales reporting system. and many other subsystems.

- WooCommerce PDF Invoices & Packing Slips Thai Language Pack (Adds Thai font (Norasi) to WooCommerce PDF Invoices & Packing Slips)

- **PDF Invoices & Packing Slips for WooCommerce**
It will be a plugin to add a PDF invoice to send along with the order confirmation email that will be sent to the customer. Comes with templates and can also customize the appearance or create our own templates.

- **PeproDev WooCommerce Receipt Uploader**
Upload Receipt for Any Payment method in WooCommerce. Customers will Upload the receipt (image/pdf) and Shop Managers will approve/reject it manually.

## Website overview

### HomePage

![Digram img](img/1.PNG)
![Digram img](img/2.PNG)
![Digram img](img/3.PNG)
![Digram img](img/4.PNG)
![Digram img](img/5.PNG)

#### Shoppage

![Digram img](img/6.PNG)

#### Cart

![Digram img](img/7.PNG)

# BPMN Diagram

![Digram img](img/All.PNG)
This BPMN diagram shows my ecommerce website process. It showcases key interactions and workflows that enhance the platform's user-friendly online coffee shop experience.

### All Pools in BPMN
- Customer
- Website
- Admin
- Delivery

#### Customer pool
![Digram img](img/Customer.png)

- Start with the green dot. It marks the beginning of the customer journey on the platform.
- Select Products: The customer selects the desired products from the available options.
![Digram img](img/6.PNG)
- Add product to cart: After selecting the product step The customer checks in to the cart. If the customer is satisfied with the selected product They will go through the payment process. If the customer still hesitates in choosing a product, the customer can cancel the product or go back and select it again.
![Digram img](img/7.PNG)

- Checkout Process: The process to Checkout the product.  (The customer fill their shipping detail.)
  - **Fill the shipping detail:** The customer fill their shipping detail.
![Digram img](img/CheckOut.PNG)
 - **Identify payment method:** customer choose the payment method. In my wetsite have 2 ways are 2C2P, and Bank transfer.
![Digram img](img/Addorder.PNG)
- Payment Process: There are 2 methods to choose from. The first method is cash on delivery. The second method is a bank transfer. Customers can pay at their convenience. (Destination or bank transfer) for bank transfer Customers can send proof of transfer right away. We will have a place to send evidence to you. If the customer pays on delivery, the customer waits to pay when the driver comes to deliver the product.
![Digram img](img/Tnk.PNG)

#### Website pool
![Digram img](img/Website.png)


#### For website it is the center between customer and admin.
- Start form the first that is product information is that can make customer choes it.
- Second is taking customer order before the data go to backend.
- Third is taking slip from customer who choes transfer before the data go to backend.
- 
#### Admin pool
![Digram img](img/Admin.png)

- **Add product:** This task represents the process of adding a new product to your e-commerce store's catalog. It includes entering product details, assigning categories, and setting pricing.
![Digram img](img/Add.png)

- **Publish Product:** :This task involves making the approved product visible to customers on the website. It ensures that the product is included in relevant search results and categories.
- **Update Product Information:** This task allows admins to modify existing product details, such as descriptions, prices, or images. It's used for maintaining accurate product information.
- **Remove Product:** When a product is discontinued or permanently out of stock, this task is used to remove the product from the website. It ensures customers can no longer purchase the item.
![Digram img](img/product.png)

- **Check order:** Admin will check the order list to see if there are any new orders or not. If there is a new order, the admin will go to the next task.
![Digram img](img/order.png)

- **Check slip and confirm order process:** This process admin will check the slip of payment and confirm order.
![Digram img](img/edit.png)

- **Correct gataway:** when admin check correctness about payment. If correct, It will go to Check Stock process. If not correct, It will cancel the order.
- The next step will be preparing the customer's order. Pack the product well so that it is not damaged during the delivery.
- Next, the order will be sent to the shipping company.

#### Delivery pool
![Digram img](img/Delivery.png)


- The shipping company receives orders from admins in order to deliver goods to customers.
- Next, the parcel number will be sent to the admin in order for the admin to send the parcel number to his customers.
- Next, the product will be sent to the customer in at least approximately 3 days (if we make payment on delivery, we can wait to pay for shipping).

#### Summary
- YEAH  e-commerce website is a testament to the power of digital transformation in the world of YEAH COFF. It combines the flexibility and user-friendly nature of WordPress and WooCommerce with careful customization and strategic plugin integration.
