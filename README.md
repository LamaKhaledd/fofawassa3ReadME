<a name="readme-top"></a>
<div align="center">
     <br>
   <br>
  <img src="nmnm.PNG" alt="Description of the image">
</div>
<div align="center">
  <br>
  <h1>Peer-to-Peer Rental Platform for Everyday Items</h1> &nbsp;<br>
</div>
<div align="center">
  <img src="lama3ametrazan.PNG" alt="Description of the image">
</div>
<br>
<br>




<a name="intro"></a>
## 🌟 About the Project
<strong>RentItOut</strong> is a peer-to-peer rental platform designed to make renting everyday items easy, reliable, and efficient. It connects people who have items to rent with those who need them, facilitating a convenient and cost-effective way to access products without purchasing them. The goal is to create a circular economy that encourages sharing and reduces the need for people to purchase items they only need occasionally.
<br>
<br>
<br>


<details>
  <summary><h2>💳 Table of Contents<h2\></summary>
  <ol>
    <li><a href="#intro">Introduction (What's RentItOut?)</a></li>
    <li><a href="#coref">Core Features</a></li>
    <li><a href="#addf">Additional Features</a></li>
    <li><a href="#roles">Roles</a></li>
    <li><a href="#bw">Built With</a></li>
    <li><a href="#gs">Getting Started</a></li>
    <li><a href="#API">API Documentation</a></li>
    <li><a href="#demo">Demo</a></li>
    <li><a href="#contribution">Contribution</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>
 <br>
 <br>
 <br>


 <a name="coref"></a>

## 2. Main Features
### 🛠️ Item Listings for Rent
- <strong> Allow users to list items they rarely use, such as tools, electronics, sports equipment, and more. Listings can be organized into various categories to facilitate item discovery.</strong>This was done by implementing CRUD operations to create, retrieve, update, and delete item listing and developing endpoints to handle different categories, enabling efficient filtering and searching.
  <br>
  
### 📊 Rental Management and Pricing
- <strong> Manage rental durations, set flexible pricing models, and allow users to specify rental periods and conditions. </strong>Define pricing and duration models in the backend by using database tables to store rental rates and durations, and develop endpoints to handle rental availability, pricing rules, and extensions.
  <br>

### 🛡️ Trust, Safety, and Verification
- <strong> User verification, rating, and review systems to ensure safe and reliable transactions. Develop mechanisms for security deposits or damage protection. </strong>Integrate identity verification for users, potentially via third-party verification APIs. 
  <br>
  
### 🚚 Logistics: Delivery and Pickup
- <strong> Provide options for delivery or in-person pickup, with the potential for location-based matchmaking to facilitate exchanges. </strong>Integrate map-based location services to assist with pickup arrangements and delivery logistics.
  <br>

### 💰 Revenue Model and Insurance
- <strong> Define how the platform generates revenue, such as through service fees. Integrate insurance or damage protection. </strong>Calculate and implement platform fees or commissions for each transaction. 
  <br>

### ⭐ User Experience and Recommendations
- <strong> Enhance the user experience by offering personalized recommendations and a user-friendly interface.</strong> Leverage data on user interactions and item popularity to provide recommendations. 
  <br>
 <br>
 <br>
 <br>


# 👥 Roles:
- 👤 **Renter**: Users who rent out items.
- 👥 **Borrower**: Users who borrow items.
- 🔧 **Admin**: Users who manage the platform.
- 🏬 **Store Owner**: Users who own stores and rent items.
- 🏷️ **Supplier**: Users who supply items for rent.
- 💼 **Beneficiary**: Users who benefit from rented items.
  <br>
 <br>
 <br>




<a name="gs"></a>
## 🚀 Getting Started
### ⚙️ Running the project
#### To get started with the project:
##### 1. Clone the repository:
> [![Github][Github]][wewe]
>
> ```sh
> git clone https://github.com/shahdyaseen/Advanced-Software.git
> ```
##### 2. Install Dependencies
Make sure you have Maven installed. Run the following command to install the necessary dependencies:
>
> ```sh
> mvn clean install
> ```
##### 3. Create The Database:
* Make sure MySQL is installed and running on your local machine.
* Create a new database for the project:
>
> ```sh
> CREATE DATABASE advanced_software;
> ```
* Update the application.properties or application.yml file in the src/main/resources directory with your MySQL database credentials (username and password).
>
> ```sh
> spring.datasource.url=jdbc:mysql://localhost:3306/advanced_software
> spring.datasource.username=your_mysql_username
> spring.datasource.password=your_mysql_password
> ```
##### 4. Run The Application:
>
> ```sh
> mvn spring-boot:run
> ```

<br>
<br>





[Spring-boot]: https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white
[SpringURL]: https://spring.io/projects/spring-boot
[GithubURL]: https://github.com/
[Postman]: https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white
[PostmanURL]: https://www.postman.com/
[wewe]: https://github.com/shahdyaseen/Advanced-Software.git
[JQuery-url]: https://jquery.com 


[Github]: https://user-images.githubusercontent.com/25181517/192108374-8da61ba1-99ec-41d7-80b8-fb2f7c0a4948.png
