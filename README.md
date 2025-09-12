A My Food App website made using Java, JDBC, JSP and servlets.

I made this project during my 6th semester for my Java Practical course. My Food App is a simple online food ordering System Built using Java,Servlets,HTML,CSS and MySQL.It allows users to browse food items, add them to cart and place an order. Admins can manage menu items and View orders.

🚀 Features

✅ User Registration & Login

✅ Browse Menu & Add to Cart

✅ Place Online Orders

✅ Admin Dashboard to Manage Food Items

✅ Responsive UI with HTML & CSS

🛠️ Tech Stack

✅Frontend: HTML, CSS, JSP

✅Backend: Java Servlets

✅Database: MySQL

✅Server: Apache Tomcat

⚙️ How to Run the Project

1.Download or clone this repository.

2.Import the project into Eclipse IDE.

3.Set up Apache Tomcat (v9 or above).

4.Import the provided SQL file into MySQL database.

5.Update the database connection details in DBConnection.java.

6.Run the project on Tomcat server and open in browser.

✨ Future Enhancements

✅Online payment integration

✅Order tracking system

✅Email/SMS notification

Now, coming to the database part of the application. I used MYSQL to create my database and tables. It was connected to my java code using JDBC.
The following are the tables which were created in the db.
Tables in onlinefoodorderdb

 >> customer

 >> drinkOrder

 >> drinks

 >> food

 >> foodOrder

 >> totalOrder

>> customer table
Schema is as follows
 
 > customer_id

 > customer_name

 > customer_emailID

 > customer_password

 > customer_address


>> drinks table
Schema is as follows

 > drink_id

 > drink_name

 > drink_price

>> food table
Schema is as follows

 > food_id

 > food_name

 > food_price

>> drinkOrder table
Schema is as follows

 > DO_id

 > order_id

 > drink_id

 > qty

 > total_price

>> foodOrder table
Schema is as follows
 
 > FO_id

 > order_id

 > food_id

 > qty

 > total_price

>> totalOrder table
Schema is as follows

 > order_id

 > customer_id

 > order_date

 > total_bill




