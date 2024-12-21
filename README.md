# Dioukou Sissoko

## CST-452 Senior Project II

### Grand Canyon University

**Instructor:** Professor Scott Webster  
**Revision:** 6.0  
**Milestone5:** Final Project Completion and Presentation (Release Phase)
**Date:** 12/22/2024  

---

## ABSTRACT

The Online Store Website Development project aims to build a fully functional online e-commerce platform tailored to small businesses. This current project will include the building of a responsive website that will allow users or shoppers to browse products by categories or to search for products, add items to a shopping cart, and complete a secure purchase. Thus, since online presence is important, the project addresses the growing demand for small businesses which enabled them to reach a large audience and continue to increase sales. Finally, the project will be designed to make user-friendly interfaces and secure online stores ready for deployment worldwide. 


---

## Porject Projection and Completion timeline

### Change Record

| Date       | Author             | Revision Notes                       |
|------------|--------------------|--------------------------------------|
| 12/01/2024 | Dioukou Sissoko    | Developement (Coding Phase)          |
| 12/15/2024 | Dioukou Sissoko    | Milestone 5: Testing (Testing phase)           |
| **12/22/2024 | Dioukou Sissoko    | Benchmark - Milestone 6: Final Project Completion and Presentation (Release Phase)  design **                 |
| 01/05/2025 | Dioukou Sissoko    | Milestone 6: Final Project Completion and Presentation (Release Phase)               |

### Overall Instructor Feedback/Comments

Integrated Instructor Feedback into Project Documentation

☐ Yes  ☐ No 

---

## TABLE OF CONTENTS

1. [Detailed High-Level Solution Design](#detailed-high-level-solution-design)
2. [Detailed Technical Design](#detailed-technical-design)
---

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
![UML Flow Diagram](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/UMLflow_diagram.png)
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
| 3 - Order Processing and Checkout Flow           | To validate the order process, including product selection and confirmation. | The entire checkout process was tested and functions correctly, from cart to order confirmation. |
| 4 - API Integration for Data Retrieval           | To verify the API's ability to fetch product data from the backend and display it on the frontend. | Data was retrieved and displayed successfully with no latency issues; API routes working as expected. |
| 5 - Product Management                            | To use CRUD operation to test the ability to add, edit, and delete products from the catalog. | CRUD operations are fully functional; products can be managed, and updates are reflected in the UI. 

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
![UML Flow Diagram](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/FlowChartsProcessFlows.png)
---
### Sitemap Diagram: 
![Sitemap Diagram](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/AfricsTouch_SITEmap.png)
---
### User Interface Diagrams: 
- **HOMEPAGE:**
![HOMEPAGE](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/UI_ContactPage.png)
---
- **CONTACT:**
![CONTACT](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/UI_ContactPage.png)
---
- **REGISTER:**
![REGISTER](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/UI_RegisterPage.png)
---

### UML Diagrams: 
![UML Diagrams](https://github.com/Lediouk/CST452_SrEcomProject/blob/main/AfricTouch_UMLDiagram.png)

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
## Test Cases

| Test Case ID | Test Case Name                | Steps                                                                 | Input/Output                      | Expected Outcome                                                                 | Result |
|-------------|-------------------------------|-----------------------------------------------------------------------|-----------------------------------|---------------------------------------------------------------------------------|--------|
| 1           | Add product                   | 1. Navigate to admin product creation page. <br> 2. Fill in product details <br> 3. Click "Submit" button | Product details: Name, Brand, Category, Price, Description, Image | Product added successfully and visible in product list. | Pass   |
| 2           | Remove Product                | 1. Navigate to Admin product list. <br> 2. Click "Remove" next to product. | Product ID | Product removed successfully and no longer visible in product list. | Pass   |
| 3           | Update Product                | 1. Navigate to admin product edit page. <br> 2. Update Name, Price fields and save. | Product Name, Price | Name and price updated correctly in the product list. | Pass   |
| 4           | User Login                    | 1. Navigate to login page. <br> 2. Enter valid credentials. <br> 3. Click "Login". | Email, Password | User logged in successfully and redirected to home page. | Pass   |
| 5           | User Registration             | 1. Navigate to registration page. <br> 2. Fill in registration details. <br> 3. Click "Register". | User details: Name, Phone, Email, Password, Address | User registered successfully and redirected to home. | Pass   |
| 6           | View User Profile             | 1. Navigate to user profile page. | Sign in user with email and password | User profile details displayed correctly. | Pass   |
| 7           | Update User Profile           | 1. Navigate to user profile page. <br> 2. Update details and save. | User details: Name, Email, Phone, Address | User profile updated successfully and changes reflected in profile. | Pass   |
| 8           | JWT Authentication Verification | 1. Perform login. <br> 2. Check token in storage. | JWT token | Token generated and stored in localStorage or sessionStorage correctly. | Pass   |

---

## Conclusion
- The e-commerce web application developed in this phase ensures a complete, responsive experience for the users and allows effective management for administrators. 
- Each feature from login, product display, User profile managemen. Note, that authentication system is secured with JWT to ensure safe user access.
- Moving forward, more testing and optimization to improve performance and scalability.

- ---

## Appendix A - Technical Issue and Risk Log

| Issue ID | Description | Likelihood | Impact | Action | Status |
|----------|-------------|------------|--------|--------|--------|
| 1        | API latency issue | Medium | Medium | Optimize API calls | In Progress |
| 2        | Product image not loading | Low | Low | Verify image paths | Fixed |
| 3        | User authentication failure | High | High | Review token storage | Fixed |

---
## Project Mapping Code:

### **africstouchecomstore & africstouchecomstore-api** 
```plaintext
africstouchecomstore/  
├── node_modules/  
├── public/  
│   ├── images/  
│   ├── favicon.ico  
│   ├── manifest.json  
│   └── robots.txt  
├── src/  
│   ├── components/  
│   │   └── layout/  
│   │       ├── Footer.js  
│   │       ├── Navbar.js  
│   │       ├── layout.js  
│   │       ├── authorization.js  
│   ├── pages/  
│   │   ├── Home.js  
│   │   ├── Contact.js  
│   │   ├── NotFound.js  
│   │   ├── ProductDetails.js  
│   │   ├── UserProfile.js  
│   │   ├── admin/  
│   │   │   └── products/  
│   │   │       ├── CreateProduct.js  
│   │   │       ├── EditProduct.js  
│   │   │       ├── ProductList.js  
│   │   │   └── users/  
│   │   │       ├── UserDetails.js  
│   │   │       ├── UserList.js  
│   ├── auth/  
│   │   ├── Login.js  
│   │   ├── Register.js  
│   ├── App.js  
│   ├── AppContext.js  
│   ├── index.js  
├── hashPassword.js  
├── package-lock.json  
├── package.json  
├── source_code.code-workspace  
├── README.md  

africstouchecomstore-api/  
├── node_modules/  
├── public/  
│   └── images/  
├── africtouchecomstoreDB.json  
├── africtouchecomstoreServer.js  
├── package-lock.json  
├── package.json  
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
