## A. Introduction
Amidst the vast innovation of technology in today’s era, by creating the Flower Shop Online enables the people who love a plethora of flowers to be delivered at their homes just by a tap from their gadgets. The platform allows the customers to take online reservations and online shopping which is a great idea for the people who love a flower to be delivered in their garden just by being at home. By creating this platform it enables the user to have an enhanced and user-friendly type of online shopping with an ease of use, simply by giving it a great UI (user interaction) and UX (user experience) layout.

## B. Project Features and Characteristics
The project (prototype) provides 2 ways of user log-in. First is the Admin Dashboard which enables the user (admin) to access how the items should be arranged, and how they would publish and update an item or remove it from the list. Admin dashboard also enables the user to easily customise the item's details and prices. Second is the User Dashboard which enables the customer to have access to what items they would like to buy or add into their wishlist (reserve item), and know the item details and prices. The user could also give feedback on the items and the service of the flower shop online.
The system also provides a search engine for the items that are in the list for a fast and simple way to navigate the item or product they need. Shopping cart are one of the best feature of the system 

## C. Project Scope
The major goal of our project is to create a profitable and engaging online flower store that provides a smooth user experience while meeting a wide range of client demands. This platform will be built around a very intuitive interface that will allow users to easily browse different flower arrangements, make safe transactions, and monitor their deliveries. The platform will provide numerous secure payment alternatives, ensuring that all transactions are handled safely and giving clients piece of mind during the purchase process. We will also develop an innovative inventory management system that updates in real time, ensuring that the goods offered for purchase represent current inventories and removing out-of-stock situations.
 Our online shop will provide a diverse assortment of quality flower arrangements designed for a variety of events, including weddings, anniversaries, birthdays, and holidays. This varied selection ensures that clients may discover the ideal bouquet for every occasion. Additionally, the site will have a review area where consumers can provide input, allowing us to enhance our offers while also supporting potential purchases in making informed choices. 
In terms of customer care, all communication and assistance will be done via the website. Customers will be able to control everything from placing an order to monitoring delivery using the web portal. Any questions or concerns will be addressed via a built-in support system, ensuring that the entire procedure is simplified and fast. By focusing completely on the website for all consumer interactions and procedures, we will build a consistent and user-friendly environment that makes buying easier.

## D. Work breakdown Structure

## E. Functional Requirements

## F. Database Architecture
### Data Dictionary

#### 1. Admin Table
| Column Name     | Data Type      | Constraints                | Description                           |
|-----------------|-----------------|-----------------------------|---------------------------------------|
| Id              | INT             | AUTO_INCREMENT              | Unique identifier for each user       |
| First Name      | VARCHAR(50)     | NOT NULL                    | User's first name                     |
| Middle Name      | VARCHAR(50)     | NULL                        | Optional middle name                 |
| Last Name       | VARCHAR(50)     | NOT NULL                    | User's last name                      |
| Email           | VARCHAR(100)    | UNIQUE, NOT NULL            | Unique email address                  |
| Password        | VARCHAR(255)    | NOT NULL                    | Hashed password                       |
| Role            | ENUM('instructor', 'administrator', 'student') | NOT NULL | Role of the user                      |
| Registered      | DATETIME        | NOT NULL                    | Timestamp of user registration        |
| Last Login      | DATETIME        | NULL                        | Timestamp of last user login          |
| Profile Picture | VARCHAR(255)    | NULL                        | URL of the user's profile picture     |

