# Dioukou Sissoko

## CST-451 Capstone Project Final Architecture & Design

### Grand Canyon University

**Instructor:** Professor Scott Webster  
**Revision:** 4.0  
**Date:** 12/01/2024  

---

## ABSTRACT

The Online Store Website Development project aims to build a fully functional online e-commerce platform tailored to small businesses. This current project will include the building of a responsive website that will allow users or shoppers to browse products by categories or to search for products, add items to a shopping cart, and complete a secure purchase. Thus, since online presence is important, the project addresses the growing demand for small businesses which enabled them to reach a large audience and continue to increase sales. Finally, the project will be designed to make user-friendly interfaces and secure online stores ready for deployment worldwide. 


---

## History and Signoff Sheet

### Change Record

| Date       | Author             | Revision Notes                       |
|------------|--------------------|--------------------------------------|
| 12/01/2024 | Dioukou Sissoko    | Developement (Coding Phase)          |
| 12/15/2024 | Dioukou Sissoko    | Milestone 5: Testing (Testing phase)           |
| 12/22/2024 | Dioukou Sissoko    | Benchmark - Milestone 6: Final Project Completion and Presentation (Release Phase) design                 |
| 1/05/2025 | Dioukou Sissoko    | Milestone 6: Final Project Completion and Presentation (Release Phase)               |

### Overall Instructor Feedback/Comments

Integrated Instructor Feedback into Project Documentation

☐ Yes  ☐ No 

---

## TABLE OF CONTENTS

1. [Design Overview](#design-overview)	4 
2. [Detailed High-Level Solution Design](#detailed-high-level-solution-design)	5 
3. [Detailed Technical Design](#detailed-technical-design)	6 
4. [Appendix A – Technical Issue and Risk Log](#appendix-a-technical-issue-and-risk-log)	7 
5. [Appendix B – References](#appendix-b-references)	8 
6. [Appendix C – External Resources](#appendix-c-external-resources)	9 

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
![UML Flow Diagram](https://github.com/Lediouk/Miletone3_EcomWebAPP/blob/main/UMLflow_diagram.png?raw=true)
---

### Tools

- **User:** Display result on any browsers such as Safari, Chrome, Firefox, or Edge 
- **Front End:** HTML5, JSX, CSS3, Bootstrap, PHP 
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

5. **Localhost Environment**  
   The entire application is run in a local environment using MAMP to simulate the real-world use cases without external hosting.

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
![UML Flow Diagram](https://github.com/Lediouk/Miletone3_EcomWebAPP/blob/main/FlowChartsProcessFlows.png)
---
### Sitemap Diagram: 
![Sitemap Diagram](https://github.com/Lediouk/Miletone3_EcomWebAPP/blob/main/Sitemap%20Diagram.png)
---
### User Interface Diagrams: 
- **HOMEPAGE:**
![HOMEPAGE](https://github.com/Lediouk/Miletone3_EcomWebAPP/blob/main/UI_Homepage.png)
---
- **CONTACT:**
![CONTACT](https://github.com/Lediouk/Miletone3_EcomWebAPP/blob/main/UI_ContactPage.png)
---
- **REGISTER:**
![REGISTER](https://github.com/Lediouk/Miletone3_EcomWebAPP/blob/main/UI_RegisterPage.png)
---
- **USER PROFILE:**
![USER](https://github.com/Lediouk/Miletone3_EcomWebAPP/blob/main/UI_RegisterPage.png)
---

### UML Diagrams: 
![UML Diagrams](https://github.com/Lediouk/Miletone3_EcomWebAPP/blob/main/UML%20Class%20Diagram.png)

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
---
