# Dioukou Sissoko

## CST-452 Senior Project II

### Grand Canyon University

**Instructor:** Professor Scott Webster  
**Revision:** 6.0  
**Milestone6:** Final Project Completion and Presentation (Release Phase)

**Date:** 12/22/2024  

---

## ABSTRACT

The Online Store Website Development project aims to build a fully functional online e-commerce platform tailored to small businesses. This current project includes the building of a responsive website that will allow users or shoppers to browse products by categories or to search for products, add items to a shopping cart, and complete a secure purchase. Thus, the platform also leverages a global state management approach using the Context API to enhance state handling across various components. 

   Since online presence is important, and to address growing demand for online presence among small businesses, the project addresses the growing demand for small businesses which enabled them to reach a large audience and continue to increase sales. Additional features were added which include a comprehensive admin section for managing products and clients, shopping card functionality and along with robust authentication mechanisms for user login and registration. Finally, the project is ultimately designed to have a user-friendly interface, and an online store that are secure and ready for deployment worldwide, which indeed enabled small businesses to thrive in the digital marketplace. 


---

## Porject Projection and Completion timeline

### Change Record

| Date       | Author             | Revision Notes                       |
|------------|--------------------|--------------------------------------|
| 12/01/2024 | Dioukou Sissoko    | Developement (Coding Phase)          |
| 12/15/2024 | Dioukou Sissoko    | Milestone 5: Testing (Testing phase)           |
| **12/22/2024** | Dioukou Sissoko    | Benchmark - Milestone 6: Final Project Completion and Presentation (Release Phase)  design                 |
| 01/05/2025 | Dioukou Sissoko    | Milestone 6: Final Project Completion and Presentation (Release Phase)               |

### Overall Instructor Feedback/Comments

Integrated Instructor Feedback into Project Documentation

☐ Yes  ☐ No 

---

## TABLE OF CONTENTS

1. [Detailed High-Level Solution Design](#detailed-high-level-solution-design)  
2. [Detailed Technical Design](#detailed-technical-design)  


## Design Introduction

This current e-commerce online web application project includes many features such as the ability of all users or shoppers when they land on our design homepage, they can browse products, shopping cart functionality, and checkout process which will be integrated later when the site is live on the internet, and friendly administrative management of products and users. The User Interface (UI) application is designed and developed using React.js, and the backend database management is fully integrated using JSON server. Most importantly, is that the robust security features include JWT authentication server for user login and management, thus ensuring secure access to all resources at ease. 

---

## Detailed High-Level Solution Design  

### Logical Solution Design Implementation  

The logical functionality solution of the e-commerce application includes many functional components:

- **User Area:** for browsing products, managing the shopping cart, and processing orders.
- **Admin Area:** for browsing products, users, and viewing processed orders.
- **Backend:** for managing product data, order processing, and services authentication.

The UML diagrams, such as data flow diagrams and functional components, describe the overall flow and interaction between frontend and backend.

---
### UML Process Flow Diagram
![UML Flow Diagram](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/CST352_Images/CST452_FinalArchitecture_AfricTouch-EcomWebApp.png)
---

### Tools

- **User:** Display result on any browsers such as Safari, Chrome, Firefox, or Edge 
- **Front End:** HTML5, JSX, React.js CSS3, Bootstrap 
- **Back End:** NodeJS, JSON Server for API and data storage 

---

## Proof of Concepts 

| Description                                      | Rationale                                                                   | Results                                                         |
|--------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------|
| 1 - Product Browsing and Filtering               | To ensure users can view and filter products efficiently using a React.js frontend and JSON API backend. | Successful implementation; users can browse and filter products |
| 2 - Secure User Authentication (JWT)             | To implement user authentication to protect user data and restrict access to certain functionalities. | JWT-based authentication verified; users can register, login, and access secure pages successfully. |
| 3 - API Integration for Data Retrieval           | To verify the API's ability to fetch product data from the backend and display it on the frontend. | Data was retrieved and displayed successfully with no latency issues; API routes working as expected. |
| 4 - Product Management                            | To use CRUD operation to test the ability to add, edit, and delete products from the catalog. | CRUD operations are fully functional; products can be managed, and updates are reflected in the UI. 

---

## Hardware and Software Technologies 

1. **Frontend:** React.js  
   Used for building a dynamic and responsive user interface for product browsing and interactions. 

2. **Backend:** JSON Server  
   Acts as a mock API and data storage system to simulate a full backend, used for CRUD operations. 

3. **Authentication:** JWT  
   JSON Web Tokens (JWT) provide secure user authentication for login and protected routes. 

4. **Database:** JSON File Storage  
   Stores product data and user information, acting as the database for the application. 

   ---

## Detailed Technical Design 

### General Technical Approach

The project follows an interactive e-commerce development approach to sell tailored design clothing to its customers. Each feature is being developed, tested, and reviewed in phases. The main phase included setting up the product browsing, cart management, and user authentication to make sure that login and transaction checkout and admin functionality are secure. 

### Key Technical Design Decisions

- **React.js:** Chosen for the front-end because of its efficiency in building dynamic UIs. 
- **JWT Authentication:** Ensures secure user sessions and access control. 
- **JSON Server:** Provides a lightweight, easy-to-use backend for CRUD operations. 

---
### Flow Charts/Process Flows: 
![UML Flow Diagram](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/CST352_Images/FlowChartsProcessFlows.png)
---
### Sitemap Diagram: 
![Sitemap Diagram](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/CST352_Images/AfricTouch_SiteMAP.PNG)
---
### User Interface Diagrams: 
- **HOMEPAGE:**
![HOMEPAGE](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/CST352_Images/Homepage_interface.PNG)
---
- **CONTACT:**
![CONTACT](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/CST352_Images/Contactpage_interface.PNG)
---
- **REGISTER:**
![REGISTER](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/CST352_Images/UserRegistration_interface.PNG)
---
- **CLIENT PROFILE:**
![CLIENT PROFILE](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/CST352_Images/Clientpage_interface.PNG)
---

### UML Diagrams: 
![UML Diagrams](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/CST352_Images/CST352_Images/UMLflow_diagram.png)

### Tools Used:

1. **React.js**  
   - **License**: MIT License ([react/LICENSE](https://github.com/facebook/react/blob/main/LICENSE))  
   - **Use Case**: Front-end development for product listings, user registration/login, shopping cart, and admin dashboard.  
   - **Reason for Use**: Strong community support, component reuse, and efficient UI management.

2. **JSON Server**  
   - **License**: MIT License ([json-server/LICENSE](https://github.com/typicode/json-server/blob/main/LICENSE))  
   - **Use Case**: Mock REST API for backend data storage and retrieval.  
   - **Reason for Use**: Quick setup for mock backend, allowing focus on front-end development.

3. **Bootstrap**  
   - **License**: MIT License ([bootstrap/LICENSE](https://github.com/twbs/bootstrap/blob/main/LICENSE))  
   - **Use Case**: Responsive UI components for navigation bars, forms, and buttons.  
   - **Reason for Use**: Ready-to-use components and a responsive grid system accelerates front-end development.
   - 
   ---
## Test Case Table

| **TC ID** | **Test Case**                      | **Steps**                                                                 | **Expected Result**                                             | **Actual Result**                                               | **Status** | **Remarks**                                                                                  |
|-----------|------------------------------------|---------------------------------------------------------------------------|------------------------------------------------------------------|------------------------------------------------------------------|------------|----------------------------------------------------------------------------------------------|
| TC1       | Add Product                       | 1. Navigate to admin product creation page. 2. Fill in product details. 3. Click "Submit". | Product added successfully and visible in product list.         | Product successfully added to the list and showing in Database. | Pass       | Ensure all required files are added with no issues.                                         |
| TC2       | Remove Product                    | 1. Navigate to admin product list. 2. Click "Remove" next to product.     | Product removed successfully and no longer visible in product list. | Product successfully removed from the list and updated as expected. | Pass       | Tested product removed successfully and is no longer visible.                              |
| TC3       | Update Product                    | 1. Navigate to admin product edit page. 2. Update Name and Price fields, then save. | Product name and price updated and visible correctly.           | Name and price updated correctly in the product list.           | Pass       | Verify that product updates are reflected correctly.                                        |
| TC4       | User Login                        | 1. Navigate to login page. 2. Enter valid credentials. 3. Click "Login".  | User logged in successfully and redirected to home page.        | User logged in successfully.                                    | Pass       | Verify users can log in with valid credentials.                                             |
| TC5       | User Registration                 | 1. Navigate to registration page. 2. Fill in registration details. 3. Click "Register". | User registered successfully and redirected to home.            | User registration completed with no issues.                    | Pass       | Verify all mandatory fields are filled.                                                     |
| TC6       | View User Profile                 | 1. Navigate to user profile page.                                         | User profile details displayed correctly.                       | User profile details displayed correctly.                       | Pass       | Ensure correct user details are displayed.                                                  |
| TC7       | Update User Profile               | 1. Navigate to user profile page. 2. Update details and save.             | User profile updated successfully and changes reflected.         | Changes reflected successfully in the user profile.             | Pass       | Ensure updates are saved correctly.                                                         |
| TC8       | JWT Authentication Verification   | 1. Perform login. 2. Access protected route with JWT token.              | Access to protected route granted.                              | Access to protected route granted.                              | Pass       | Ensure JWT token is valid and active.                                                       |
| TC9       | Product Search Functionality      | 1. Navigate to product search page. 2. Enter search term. 3. Click "Browse". | Relevant products displayed based on search term.               | Relevant products displayed based on search term.               | Pass       | Ensure search results are accurate.                                                         |
| TC10      | Product Sorting Functionality     | 1. Navigate to product list page. 2. Select sort criteria.                | Products sorted based on selected criteria.                     | Products sorted successfully based on selected criteria.         | Pass       | Verify sorting functionality works correctly.                                               |
| TC11      | Pagination in Product List        | 1. Navigate to product list page. 2. Navigate through pages.              | Products displayed correctly in paginated format.               | Products displayed correctly in paginated format.               | Pass       | Ensure pagination is implemented correctly.                                                 |
| TC12      | Contact Form Submission           | 1. Navigate to contact page. 2. Fill in contact form details. 3. Click "Submit". | Contact form successfully implemented and data received in DB.  | Data received successfully.                                    | Pass       | Ensure contact form functionality works properly.                                           |
| TC13      | Admin User Management             | 1. Navigate to admin user management page. 2. View list of customers/users. | List of users displayed correctly, with roles defined.          | Users and roles displayed correctly.                           | Pass       | Ensure all user management functionalities work.                                            |
| TC14      | User Logout                       | 1. Perform sign-in. 2. Click "Logout" button.                             | User and admin logged out successfully and redirected to home.  | Both user/admin logged out successfully.                       | Pass       | Verify user session is cleared on logout.                                                   |
| TC15      | Refresh Button                    | 1. Navigate to any page with a refresh button. 2. Click on the refresh button. | Page refreshes and displays updated content.                    | Page does not refresh or display updated content.               | Fail       | Ensure refresh button functionality works.                                                  |
| TC16      | Admin Product Update              | 1. Navigate to admin product list. 2. Click "Update" next to a product. 3. Save changes. | Product updated successfully and changes reflected in details.  | Product details updated successfully.                          | Pass       | Ensure updates are saved correctly.                                                         |
| TC17      | View Product Details              | 1. Navigate to product details page.                                      | Product details displayed correctly.                            | Product details displayed correctly.                            | Pass       | Ensure correct product details are displayed.                                               |
| TC18      | User Password Update              | 1. Navigate to user profile page. 2. Update password and submit.          | Password updated successfully and usable for login.             | User can log in with the new password.                         | Pass       | Ensure password update functionality works.                                                 |
| TC19      | Social Media Link Clicks          | 1. Navigate to any page with social media links. 2. Click on the links.   | Social media pages open successfully.                           | Social media pages open successfully.                           | Pass       | Ensure social media links are functional.                                                   |


- ---

## Appendix A - Technical Issue and Risk Log

| Issue ID | Description | Likelihood | Impact | Action | Status |
|----------|-------------|------------|--------|--------|--------|
| 1        | API latency issue | Medium | Medium | Optimize API calls | Resolved |
| 2        | Product image not loading | Low | Low | Verify image paths | Resolved |
| 3        | User authentication failure | High | High | Review token storage | Resolved |

---
## Project Mapping Code:

### **africstouchecomstore & africstouchecomstore-api** 
```plaintext
\CST452-SrProjectApp \ africstouchecomstore\    # Senior Project App directory 

├── africstouchecomstore/      		      # Front-end directory (React app) 
│   ├── build/                    		   # Compiled production-ready files  
│   ├── node_modules/            		   # Project dependencies installed by npm 
│   ├── public/                   		   # Publicly accessible files and assets 
│   │   ├── images/               		   # Folder for image assets 
│   │   ├── favicon.ico           		   # Icon for the website 
│   │   ├── manifest.json         		   # Manifest for PWA (Progressive Web App) 
│   │   └── robots.txt            		   # Instructions for search engine bots 
│   ├── src/                      		   # Source code for the React app 
│   │   ├── components/           		   # Reusable components 
│   │   │   ├── Authorization.js  	      # Logic for authorization (login, register) 
│   │   │   └── FrontLayout.js   			# Layout component logic (was layout.js) 
│   │   ├── pages/                			# Components representing different pages 
│   │   │   ├── Homepage.js       		   # Homepage of the app 
│   │   │   ├── Contact.js        			# Contact page 
│   │   │   ├── ErrorPageAccess.js 		   # Error page for access issues 
│   │   │   ├── ProductDetails.js 		   # Page displaying product details 
│   │   │   ├── ClientProfile.js  			# Client profile page (replacing User Profile) 
│   │   │   ├── admin/            			# Admin section pages 
│   │   │   │   ├── products/     			# Folder for managing products 
│   │   │   │   │   ├── CreateProduct.js 	# Page for creating products 
│   │   │   │   │   ├── UpdateProduct.js 	# Page for updating products 
│   │   │   │   │   └── ProductList.js   	# Page displaying list of products 
│   │   │   │   ├── clients/      			# Folder for managing clients 
│   │   │   │   │   ├── ClientDetails.js 	# Page for displaying client details 
│   │   │   │   │   └── ClientList.js    	# Page displaying list of clients 
│   │   │   └── authentication/   		   # Authentication-related pages 
│   │   │       ├── Signin.js     			# Sign in page for existing users 
│   │   │       └── Signup.js     			# Signup page for new users 
│   │   ├── GlobalContext.js       		   # Global state using React Context API 
│   │   ├── index.js               			# Entry point of the React application 
│   ├── hashPassword.js            		   # Utility for hashing passwords 
│   ├── package.json               			# Dependencies, scripts, and metadata 
│   ├── package-lock.json          		   # Exact version of dependencies installed 
│   ├── README.md                  		   # Project documentation 

\CST452-SrProjectApp \ africstouchecomstore-api\  
├── africstouchecomstore-api/      		# API directory for the project 
│   ├── node_modules/             		# Project dependencies installed by npm 
│   ├── public/                   			# Publicly accessible files and assets 
│   │   └── images/               			# Folder for image assets 
│   ├── africtouchecomstoreDB.json 		# Database file for the backend (JSON format) 
│   ├── africtouchecomstoreServer.js		# Server file for API (Node.js/Express) 
│   ├── package-lock.json         		# Exact version of dependencies installed 
│   ├── package.json              			# Dependencies, scripts, API metadata  
```
### **Completed Final Project:**
- Fully commented source code and executable
- Project artifacts (Proposal, Requirements, Architecture Plan)
- Functional demo and presentation
- README with Git repository link, demonstrating source control best practices
- Internet-facing Project Portfolio showcasing the project for potential employers

- ---

## Appendix B - References

1. React.js Documentation, [reactjs.org](https://reactjs.org/docs/getting-started.html)
2. JWT Authentication Guide, [jwt.io](https://jwt.io/introduction/)

---
## Appendix C - External Resources
1. Free API Data for Product Listings - [mockaroo.com](https://www.mockaroo.com/)
2. Online Authentication Tutorial - [dev.to](https://dev.to/)

3. ---

## Conclusion
- The e-commerce web application developed in this phase ensures a complete, responsive experience for the users and allows effective management for administrators. 
- Each feature from login, product display, User profile managemen. Note, that authentication system is secured with JWT to ensure safe user access.
- Moving forward, more testing and optimization to improve performance and scalability.
---
## NEXT FINAL WEEK  
1. DATE: (12/30/2024 to 01/05/2024)
   
**Planned Key Deliverables**
- Begin final debugging and unit testing on December 30, 2024. 
- Incorporate beta test feedback and finalize all application features by January 2, 2025. 
- Prepare and rehearse the final presentation to ensure a professional delivery on January 5, 2025. 
