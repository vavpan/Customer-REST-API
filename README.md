# Customer-REST-API

<b>About the API</b>
<p> An API for customer management. It is built with Java,Spring Boot and Spring Framework. You can view,update,add and delete customers who are stored in a database.</p>

<b>Features</b>
<ul>
<li>Get a list of customers: GET/api/customers </li>
<li>Get a single customer by id: GET/api/customers/1 </li>
<li>Add a new customer: POST/api/customers (Add the values you want)</li>
<li>Update a customer: PUT/api/customers (Change the values you want) </li>
<li>Delete a customers: DELETE/api/customers/1 </li>

</ul>

<b> Technologies used </b>
<ul>
<li>Java</li>
<li>Spring Boot</li>
<li>Spring Web MVC</li>
<li>Hibernate</li>
<li>MySQL</li>
<li>Maven</li>
<li>Jackson</li>
<li>JSON</li>
<li>Tomcat 9.0</li>

</ul>


<b> Execution </b>

<p> You need to have MySQL Workbench installed on your machine to save the customer database. After installed, you can find the SQL script in source code in folder "Database". Run the script in Workbench in order the database to be created.

After creating the API database, you need to go to <u>persistence-mysql.properties</u> file on <u>src/main/resource</u>. The lines that must be modified are as follows:

jdbc.user= 
<br>
jdbc.password=

Thereafter, you have to install Tomcat 9.0 on your computer in order to run the application. Once it's done, you can run the Customer API. For a better experience you can use Postman(it is optional) in order to manage the customers.
