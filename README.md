LuLuOnlineMall
======
This is an e-commerce project built using Java MVC architecture, MySQL database, FTP file server, and Maven. 
Mybatis is used for data access and Nginx is used for load balancing. The payment module is integrated with the Alipay payment API.

Functionality:
----
1.User module: users can register, login, modify personal information, reset passwords, etc. Passwords are encrypted using MD5 technology.

2.Category management module: administrators can add, modify, and delete product categories.

3.Product management module: administrators can add, modify, and delete products. Users can view product listings, product details, and product reviews. The product list supports dynamic pagination, and the backend supports product upload.

4.Shopping cart module: users can add products to the shopping cart, modify the quantity of products in the shopping cart, delete products from the shopping cart, etc.

5.Shipping address management module: users can add, modify, and delete shipping addresses.

6.Payment module: users can select a payment method and make payments using the Alipay payment API.

7.Order management module: administrators can create, cancel, view order lists, order details, and ship orders.

Technology Stack:
----
Java 8

MVC

MySQL

FTP

Mybatis

Nginx

Alipay payment API

Notes：
----
1.Passwords used in the project are encrypted using MD5 technology to ensure the security of user information.

2.The payment module uses the Alipay payment API and requires appropriate configuration to use.

3.The product list supports dynamic pagination, and the number of items displayed per page and the page number can be set in the front-end.
