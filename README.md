# Dioukou Sissoko
**BACHELOR OF SCIENCE, SOFTWARE ENGINEERING** GRAND CANYON UNIVERSITY

**GPA 3.9 | DEAN’S HONOR LIST STUDENT**

**Final Revision:** 6.1  
**Ecommerce Website Application :** Project Completion and Presentation (Release Phase)  
**Release Date:** 01/05/2025

---

## ABSTRACT

The Online Store Website Development project aims to build a fully functional online e-commerce platform tailored to small businesses. This current project includes the building of a responsive website that will allow users or shoppers to browse products by categories or to search for products, add items to a shopping cart, and complete a secure purchase. Thus, the platform also leverages a global state management approach using the Context API to enhance state handling across various components.

Since online presence is important, and to address growing demand for online presence among small businesses, the project addresses the growing demand for small businesses which enabled them to reach a large audience and continue to increase sales. Additional features were added which include a comprehensive admin section for managing products and clients, shopping card functionality and along with robust authentication mechanisms for user login and registration. Finally, the project is ultimately designed to have a user-friendly interface, and an online store that are secure and ready for deployment worldwide, which indeed enabled small businesses to thrive in the digital marketplace.



---

# History and Signoff Sheet

| Date        | Author           | Revision Notes                                   |
|-------------|------------------|-------------------------------------------------|
| 12/01/2024  | Dioukou Sissoko  | Development Phase (Coding)                      |
| 12/15/2024  | Dioukou Sissoko  | Testing (Testing Phase)                         |
| 12/22/2024  | Dioukou Sissoko  | Project Completion and Presentation (Release Phase) |
| 01/05/2025  | Dioukou Sissoko  | Final Architecture and Design Presentation      |


## TABLE OF CONTENTS
- **Design Overview**  
- **Detailed High-Level Solution Design** 
- **Detailed Technical Design** 
- **APPENDIX A – Reference**
- **APPENDIX B – Copyright and Compliance**


## Design Introduction

This current e-commerce online web application project includes many features such as the ability of all users or shoppers when they land on our design homepage, they can browse products, shopping cart functionality, and checkout process, Note addtional feature when the site is live on the internet will be impletement such as different method of payment, and friendly administrative management of products and users. The User Interface (UI) application is designed and developed using React.js, and the backend database management is fully integrated using JSON server. Most importantly, is that the robust security features include JWT authentication server for user login and management, thus ensuring secure access to all resources at ease. 

---

## Detailed High-Level Solution Design  

### Logical Solution Design Implementation  

The logical functionality solution of the e-commerce application includes many functional components:

- **User Area:** for browsing products, managing the shopping cart, and processing orders.
- **Admin Area:** for browsing products, users, and viewing processed orders.
- **Backend:** for managing product data, order processing, and services authentication.

The UML diagrams, such as data flow diagrams and functional components, describe the overall flow and interaction between frontend and backend.

![Logical Design Flow](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_LogicalSolutionDesign.png)
*Figure 1: Logical Design Flow for the project updated as of 1/05/2025.*

---

### <u>Logical Design Flow</u>
![Logical Design Flow](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_FLOW_CHART.png)
*Figure 2: Logical Design Flow for the project updated as of 1/05/2025.*

---

### <u>ER Diagram Design</u>
![ER Diagram Design](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_ER_DIAGRAM.png)

*Figure 3: ER Diagram Design for the project updated as of 1/05/2025.*

---

### <u>Admin & Client Profile Data Flow</u>
![Admin & Client Profile Data Flow](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_Client-Admin_DATAFLOW.png)

*Figure 4: Admin & Client Profile Data Flow for the project updated as of 1/05/2025.*

---

### <u>Category Data Flow</u>
![Category Data Flow](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_CATEGORY_DATAFLOW.png)

*Figure 5: Category Data Flow for the project updated as of 1/05/2025.*

---

### <u>Product Data Flow</u>
![Product Data Flow](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_PRODUCT_DATAFLOW.png)

*Figure 6: Product Data Flow for the project updated as of 1/05/2025.*

---

### <u>Order Data Flow</u>
![Order Data Flow](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_ORDER_DATAFLOW.png)

*Figure 7: Order Data Flow for the project updated as of 1/05/2025.*

---
### User Interface Diagrams: 
- **HomePage:**
![HOMEPAGE](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_Homepage_interface.PNG)

*Figure 8: HomePage for the project updated as of 1/05/2025.*

---
- **Contact Page:**
![Contact Page](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_Contactpage_interface.PNG)

*Figure 9: Contact Page for the project updated as of 1/05/2025.*

---
- **Register Page:**
![Register Page](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_UserRegistration_interface.PNG)

*Figure 10: Contact Page for the project updated as of 1/05/2025.*

---
- **Client Profile Page:**
![Client Profile Page ](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/1-05-25_Client-Admin_DATAFLOW.png)

*Figure 10: Client Profile Page for the project updated as of 1/05/2025.*

---

### Tools

- **User:** Display result on any browsers such as Safari, Chrome, Firefox, or Edge 
- **Front End:** HTML5, JSX, React.js CSS3, Bootstrap 
- **Back End:** NodeJS, JSON Server for API and data storage 

---

## Proof of Concepts 

# Roof of Concepts

| **Description**                                        | **Rationale**                                                                          | **Results**                                                                 |
|--------------------------------------------------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| **1 - Product Browsing and Filtering**                | To ensure users can view and filter products efficiently using a React.js frontend and JSON API backend. | Successful implementation; users can browse and filter products.           |
| **2 - Secure User Authentication (JWT)**              | To implement user authentication to protect user data and restrict access to certain functionalities. | JWT-based authentication verified; users can register, login, and access secure pages successfully. |
| **3 - API Integration for Data Retrieval**            | To verify the API's ability to fetch product data from the backend and display it on the frontend. | Data was retrieved and displayed successfully with no latency issues; API routes working as expected. |
| **4 - Product Management**                            | To use CRUD operations to test the ability to add, edit, and delete products from the catalog. | CRUD operations are fully functional; products can be managed, and updates are reflected in the UI. |
| **5 - Shopping Cart Functionality**                   | To allow users to add, remove, and modify product quantities in their shopping cart. | Shopping cart functionality implemented; users can add, remove, and update product quantities. |
| **6 - Checkout Process**                              | To ensure users can proceed to checkout, review their cart, and complete the purchase. | Checkout process implemented; users can review their cart, apply discounts, and complete their purchase securely. |
| **7 - Frontend Structure and Layout**                 | To ensure a clean, organized, and user-friendly UI for a seamless shopping experience. | Well-structured React components; reusable components and proper layout implemented for better user experience. |
| **8 - Backend API Structure and Database**            | To ensure the backend API is well-structured and can handle data efficiently for product management and user authentication. | API endpoints functioning correctly with Node.js/Express; JSON database is used effectively for storing product and user data. |


---

# Hardware and Software Technologies

| **Category**                   | **Technologies Used**                                                                                                                                              |
|---------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Integrated Development Environment (IDE)** | Visual Studio Code for writing and managing code.                                                                                                                |
| **Version Control**             | GitHub to display projects like portfolios and track changes.                                                                                                    |
| **Frontend Development**        | JavaScript, HTML, and CSS for creating the user interface.                                                                                                       |
|                                 | React.js to simplify the development process and enhance the user experience.                                                                                   |
| **Backend Development**         | Node.js/Express for server-side operations, ensuring efficient backend functionality.                                                                             |
|                                 | JSON local data for storing and managing application data.                                                                                                      |
| **Web Browser Used**            | Chrome & Edge Developer Tools to check error network logs during testing and development.                                                                        |


   ---

### General Technical Approach

The project follows an interactive e-commerce development approach to sell tailored design clothing to its customers. Each feature is being developed, tested, and reviewed in phases. The main phase included setting up the product browsing, cart management, and user authentication to make sure that login and transaction checkout and admin functionality are secure. 

### Key Technical Design Decisions

- **React.js:** Chosen for the front-end because of its efficiency in building dynamic UIs. 
- **JWT Authentication:** Ensures secure user sessions and access control. 
- **JSON Server:** Provides a lightweight, easy-to-use backend for CRUD operations. 

---

## Test Case Table

| **Test Case ID** | **Test Case Name**               | **Test Steps**                                                                                      | **Expected Outcome**                                                            | **Actual Outcome**                                                                  | **Status** | **Comments**                                       |
|------------------|----------------------------------|-----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|------------|----------------------------------------------------|
| TC1              | Admin Login                      | 1. Navigate to the login page. <br> 2. Enter valid admin credentials. <br> 3. Click "Login"         | Admin is logged in and redirected to the admin dashboard.                         | Product successfully added to list of all products and showing also in Database     | Pass       | To cover authentication for admin users.          |
| TC2              | User Login                       | 1. Navigate to the login page. <br> 2. Enter valid user credentials. <br> 3. Click "Login"         | User is logged in and redirected to the homepage.                                | Product successfully removed from the list, and the list updated as expected        | Pass       | To cover authentication for regular users.        |
| TC3              | User Registration                | 1. Navigate to the registration page. <br> 2. Fill out the required fields. <br> 3. Click "Register" | New user account created, and the user is redirected to the homepage.           | Name and price updated correctly in the product list.                              | Pass       | Verifies new account creation functionality.       |
| TC4              | JWT Token Authentication         | 1. Perform login. <br> 2. Use JWT token to access a protected API route.                           | Access to the protected API route is granted.                                    | User logged in successfully                                                         | Pass       | Access to the protected API route is granted.     |
| TC5              | Update User Profile              | 1. Navigate to the profile page. <br> 2. Update user details and save changes.                      | Updated profile details are saved and displayed correctly.                       | Updated profile details are saved successfully and displayed correctly.            | Pass       | Ensures correct saving of updated user profile info. |
| TC6              | Update User Password             | 1. Navigate to the profile page. <br> 2. Enter a new password and save changes. <br> 3. Login again | User password updated successfully and details displayed correctly.             | Pass                                                                                 | Verifies password update functionality.           |
| TC7              | Add Product                      | 1. Navigate to the admin product creation page. <br> 2. Enter product details. <br> 3. Click "Submit" | Product is added to the list and stored in the database.                         | Successfully confirmed that added successfully and changes reflected               | Pass       | Verifies adding a new product functionality.       |
| TC8              | Update Product                   | 1. Navigate to the admin product list. <br> 2. Click "Update" for a product. <br> 3. Save changes     | Updated product details are displayed correctly in the list.                    | Updated product details are displayed correctly in the list.                       | Pass       | Ensures product updates are saved correctly.       |
| TC9              | Remove Product                   | 1. Navigate to the admin product list. <br> 2. Click "Remove" for a product.                         | Product is removed from the list and deleted from the database.                  | Product is removed from the list and deleted from the database.                     | Pass       | Verifies product removal functionality.            |
| TC10             | View Product Details             | 1. Navigate to the product details page.                                                             | Product details (e.g., name, price, description) are displayed correctly.       | Product details (e.g., name, price, description) are displayed correctly.          | Pass       | Ensures accurate display of product details.       |
| TC11             | Product Search                   | 1. Navigate to the product search page. <br> 2. Enter a search term. <br> 3. Click "Search"          | Relevant products matching the search term are displayed.                       | Relevant products matching the search term are displayed.                          | Pass       | Validates product search functionality.           |
| TC12             | Product Sorting                  | 1. Navigate to the product list. <br> 2. Select a sorting option (e.g., brand, category, price, etc.).| Products are sorted based on the selected criteria.                              | Products are sorted based on the selected criteria.                                 | Pass       | Ensures product sorting works as expected.         |
| TC13             | Product Pagination               | 1. Navigate to the product list. <br> 2. Browse through pages.                                     | Products are displayed correctly in a paginated format.                          | Products are displayed correctly in a paginated format.                             | Pass       | Verifies proper implementation of pagination.      |
| TC14             | Contact Form Submission          | 1. Navigate to the contact page. <br> 2. Fill in the contact form. <br> 3. Click "Submit"            | Contact form submission is successful, and data is stored in the database.      | Contact form submission is successful, and data is stored in the database.         | Pass       | Ensures contact form functionality.                |
| TC15             | About Page                       | 1. Navigate to the About page.                                                                        | Information about the store is displayed.                                        | Page does not refresh or display updated content.                                  | Pass       | Verifies display of About page content.            |
| TC16             | Admin User Management            | 1. Navigate to the admin user management page. <br> 2. View user list.                              | User list is displayed, including roles.                                         | User list is displayed, including roles.                                            | Pass       | Validates admin user management functionality.     |
| TC17             | Social Media Links               | 1. Click on any social media link on a page.                                                         | Link redirects correctly.                                                         | Link only refreshes with a blank # symbol and no redirect.                         | Pass       | Ensures social media links redirect correctly.     |
| TC18             | Page Refresh Button              | 1. Navigate to a page with a refresh button. <br> 2. Click "Refresh"                                | Page refreshes and displays updated content.                                     | Page refreshes and displays updated content.                                        | Pass       | Verifies refresh button functionality.            |
| TC19             | JWT API Access                   | 1. Use a valid JWT token to access a backend API route.                                              | Access to the protected API route is granted.                                    | Access to the protected API route is granted.                                        | Pass       | Verifies API access with valid authentication.    |
| TC20             | Database Integration             | 1. Perform CRUD operations (add, update, delete) on products.                                        | Store information displayed successfully for more details                       | CRUD operations performed successfully and updates displayed                        | Pass       | Ensures database updates for CRUD operations.     |


- ---

## Project Mapping Code:

### **africstouchecomstore & africstouchecomstore-api** 
```plaintext
\CST452-SrProjectApp \ africstouchecomstore\    # Senior Project App directory 

├── africstouchecomstore/        	      # Front-end directory (React app)  
│   ├── build/                  			   # Compiled production-ready files   
│   ├── node_modules/            		   # Project dependencies installed by npm  
│   ├── public/                  		   # Publicly accessible files and assets  
│   │   ├── images/              		   # Folder for image assets  
│   │   ├── manifest.json        	      # Manifest Progressive Web Application 
│   │   └── robots.txt           		   # Instructions for search engine bots  
│   ├── src/                     		   # Source code for the React app  
│   │   ├── components/          		   # Reusable components  
│   │   │   ├── Authorization.js 		   # Logic for authorization (login, register)  
│   │   │   ├── FrontLayout.js   		   # Layout component logic  
│   │   │   └── Cart.js          		   # Shopping cart component  
│   │   ├── pages/               		   # Components representing pages  
│   │   │   ├── Homepage.js      		   # Homepage of the app  
│   │   │   ├── Contact.js       		   # Contact page  
│   │   │   ├── ErrorPageAccess.js		   # Error page for access issues  
│   │   │   ├── ProductDetails.js		   # Page displaying product details  
│   │   │   ├── ClientProfile.js 		   # Client profile page   
│   │   │   ├── admin/          	 		   # Admin section pages  
│   │   │   │   ├── products/    		   # Folder for managing products  
│   │   │   │   │   ├── CreateProduct.js 	# Page for creating products  
│   │   │   │   │   ├── UpdateProduct.js 	# Page for updating products  
│   │   │   │   │   └── ProductList.js  	# Page displaying list of products  
│   │   │   │   ├── clients/     			# Folder for managing clients  
│   │   │   │   │   ├── ClientDetails.js 	# Page for displaying client details  
│   │   │   │   │   └── ClientLists.js  	# Page displaying list of clients  
│   │   │   └── authentication/  	      # Authentication-related pages  
│   │   │       ├── Signin.js    			# Sign in page for existing users  
│   │   │       └── Signup.js    			# Signup page for new users  
│   │   ├── GlobalContext.js     	      # Global state using React Context API  
│   │   ├── ShoppingCartContext.js 	      # Shopping cart context (To process) 
│   │   ├── index.js                      # Entry point of the React application  
│   ├── package.json                      # Dependencies, scripts, and metadata  
│   ├── package-lock.json                 # Exact version of dependencies installed  
│   ├── README.md                         # Project documentation

\CST452-SrProjectApp \ africstouchecomstore-api\  
├── africstouchecomstore-api/      		   # API directory for the project 
│   ├── node_modules/             		   # Project dependencies installed by npm 
│   ├── public/                   			# Publicly accessible files and assets 
│   │   └── images/               			# Folder for image assets 
│   ├── africtouchecomstoreDB.json 		   # Database file for the backend (JSON format) 
│   ├── africtouchecomstoreServer.js		# Server file for API (Node.js/Express) 
│   ├── package-lock.json         		   # Exact version of dependencies installed 
│   ├── package.json            			   # Dependencies, scripts, API metadata  
```
### **Completed Final Project:**
- Fully commented source code and executable
- Project artifacts (Proposal, Requirements, Architecture Plan)
- Functional demo and presentation
- README with Git repository link, demonstrating source control best practices
- Internet-facing Project Portfolio showcasing the project for potential employers

---
## Project Schedule UPDATE 1/05/2025

### Work Breakdown Structure (WBS)

| Tasks | Duration |
|-------|----------|
| **Planning & Requirements Analysis** | 1 week |
| - Define requirements | |
| - Create project plan | |
| **Frontend Development (React.js)** | 3 weeks |
| - Set up project structure | |
| - Implement Navigation Bar | |
| - Develop User Registration/Login | |
| - Create Product Listing and Details Pages | |
| - Implement Shopping Cart & Checkout | |
| **Backend Development (JSON Server)** | 2 weeks |
| - Set up JSON Server | |
| - Create API endpoints for Products, Users | |
| - Implement Authentication Logic | |
| - Integrate with Frontend | |
| **Admin Dashboard Development** | 2 weeks |
| - Develop Admin Login | |
| - Implement Product Management | |
| - Implement User Management | |
| - Admin Profile Management | |
| **Testing & Debugging** | 2 weeks |
| - Unit Testing | |
| - Integration Testing | |
| - Added Shopping Cart (Updated) | |
| **Finalization & Documentation** | 1.5 week |
| - Document Code | |
| - Create User Manual | |
| - Final Review and Adjustments | |

### Project Timeline:

| Task | Start Date | End Date | Duration |
|------|------------|----------|----------|
| **Planning & Requirements** | 10/21/2024 | 10/27/2024 | 1 week |
| **Frontend Development** | 10/28/2024 | 11/17/2024 | 3 weeks |
| **Backend Development** | 10/28/2024 | 11/10/2024 | 2 weeks |
| **Admin Dashboard Development** | 11/11/2024 | 11/24/2024 | 2 weeks |
| **Testing & Debugging** | 11/25/2024 | 12/08/2024 | 2 weeks |
| **Finalization & Documentation** | 12/09/2024 | 12/15/2024 | 1 week |
| **Project Wrap-Up & Presentation** | 12/16/2024 | 01/05/2025 | 3 weeks |

---
## Conclusion
- The e-commerce web application developed in this phase ensures a complete, responsive experience for the users and allows effective management for administrators. 
- Each feature from login, product display, User profile managemen. Note, that authentication system is secured with JWT to ensure safe user access.
- Moving forward, more testing and optimization to improve performance and scalability.

---
## Appendix A – References

1. **Project, G.** (2021, July 26). The importance of a Christian worldview. *The Gospel Project*. [https://gospelproject.lifeway.com/the-importance-of-a-christian-worldview/](https://gospelproject.lifeway.com/the-importance-of-a-christian-worldview/)

2. **facebook.** (n.d.). react/LICENSE at main · facebook/react. *GitHub*. [https://github.com/facebook/react/blob/main/LICENSE](https://github.com/facebook/react/blob/main/LICENSE)

3. **Typicode.** (n.d.). json-server/LICENSE at main · typicode/json-server. *GitHub*. [https://github.com/typicode/json-server/blob/main/LICENSE](https://github.com/typicode/json-server/blob/main/LICENSE)

4. **Twbs.** (n.d.). bootstrap/LICENSE at main · twbs/bootstrap. *GitHub*. [https://github.com/twbs/bootstrap/blob/main/LICENSE](https://github.com/twbs/bootstrap/blob/main/LICENSE)

5. **React.js Documentation.** *React.js*. [https://reactjs.org/docs/getting-started.html](https://reactjs.org/docs/getting-started.html)

6. **JWT Authentication Guide.** *JWT.io*. [https://jwt.io/introduction/](https://jwt.io/introduction/)

---

## Appendix B – Copyright Compliance

### React.js
- **Copyright Policy:** MIT License  
- **Reference:** [react/LICENSE at main · facebook/react (github.com)](https://github.com/facebook/react/blob/main/LICENSE)  
- **Usage:** It is used for front-end development, including components for product listings, user registration/login, shopping cart, and admin dashboard.  
- **Reason for Use:** Strong community support, component reuse, and efficient UI management.

---

### JSON Server
- **Copyright Policy:** MIT License  
- **Reference:** [json-server/LICENSE at main · typicode/json-server (github.com)](https://github.com/typicode/json-server/blob/main/LICENSE)  
- **Usage:** It is most used as a Mock REST API for backend data storage and retrieval.  
- **Reason for Use:** Quick setup for mock backend, allowing focus on front-end development.

---

### Bootstrap
- **Copyright Policy:** MIT License  
- **Reference:** [bootstrap/LICENSE at main · twbs/bootstrap (github.com)](https://github.com/twbs/bootstrap/blob/main/LICENSE)  
- **Usage:** It is used for responsive UI components, including navigation bars, forms, and buttons.  
- **Reason for Use:** Ready-to-use components and responsive grid system accelerate front-end development.

---

![Logo](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/africTouch_leftImage.PNG)
