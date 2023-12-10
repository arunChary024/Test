
# Overview

This Software Requirements Specification (SRS) provides a detailed blueprint for our project, encompassing all critical aspects from Functional and Non-Functional Requirements to a Change Management Plan and a Traceability Matrix. It is designed to establish a uniform understanding among stakeholders about the project's goals, scope, and the essential criteria for its successful execution, ensuring that the system aligns with the expected features and quality standards.

# Software Requirements

The software requirements are meticulously categorized into Functional and Non-Functional sections, each outlined in tabular format for clarity. These tables include specific IDs and concise descriptions of each requirement, serving as a clear reference point for system capabilities and expected performance standards, thereby aligning closely with the project's objectives and user needs.



## Functional Requirements

### Registration and Login
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------ |
| FR1 | The system shall allow users/admin to login to the website when they click the Login button. |
| FR2 |The system shall navigate users to the account creation screen upon clicking the 'Sign Up' hyperlink on the login screen |
| FR3 | The system shall allow users to access the product browsing screen upon clicking the ShopApp button. |
| FR4 | The system shall allow account creation when the Create Account button is clicked. |
| FR5 | The system shall allow navigate users to the Login screen upon clicking the 'Sign In' hyperlink on the cart screen|
### Shopping Cart
| ID  | Requirement |
| :--:| :---------------------------------------------------------------------------------------------------- |
| FR6 | The system shall allow users to log out upon clicking the Signout icon. |
| FR7 | The system shall allow users to reduce the quantity of products in the cart by clicking the minus button on the cart screen . |
| FR8 | The system shall allow users to increase the quantity of products in the cart by clicking the plus button on the cart screen. |
| FR9 | The system shall display a pop-up confirming successful payment upon clicking the Pay Button. |
| FR10 | The system shall display user information such as name, address, and email upon clicking the Checkout button. |
### Admin and Order Management
| ID   | Requirement |
| :---:| :--------------------------------------------------------------------------------------------------------------- |
| FR11 | The system shall allow admin to navigate to the main page upon clicking the Home icon. |
| FR12 | The system shall display a list of orders upon clicking the Orders button. |
| FR13 | The system shall reveal detailed information about a selected order upon clicking the View action icon in the orders list screen. |
| FR14 | The system shall allow deletion of an order upon clicking the Delete action icon in the orders list screen. |
| FR15 | The system shall allow admin to navigate to the Products screen upon clicking the Products button on the Admin Main screen. |

### Product Browsing
| ID   | Requirement |
| :---:| :----------------------------------------------------------------------------------------------------------- |
| FR16 | The system shall allow users to navigate to the User Accounts screen upon clicking the User Account icon. |
| FR17 | The system shall allow users to search products upon entering a product name in the search bar. |
| FR18 | The system shall allow users to add items to the cart upon clicking the Add button below every product. |
| FR19 | The system shall allow users to scroll through the list of products on the product browsing screen. |
| FR20 | The system shall allow users to navigate to the cart screen upon clicking the Cart icon. |

### <Admin Product Management>
| ID   | Requirement |
| :---:| :------------------------------------------------------------------------------------------------------------------------- |
| FR21 | The system shall allow users to navigate to the Add New Products screen upon clicking the Add Products button in the products list screen. |
| FR22 | The system shall allow the addition of new products upon clicking the Add Product button on the Add New Product screen. |
| FR23 | The system shall enable users to select images from the device upon clicking the Choose File button in the Add New Product screen. |
| FR24 | The system shall allow modifications to the product name and price upon clicking the Edit action icon in the products list screen. |
| FR25 | The system shall allow removal of a product from the list upon clicking the Delete action in the products list screen. |

## Non-Functional Requirements

### User Authentication and Data Security
| ID   | Requirement |
| :---:| :----------------------------------------------------------------------------------------------------------------- |
| NFR1 | The system shall utilize Firebase Authentication for secure user login via email and password. |
| NFR2 | The system shall enforce advanced password complexity rules to enhance account security. |
| NFR3 | The system shall use Firebase Security Rules to control database and storage access, ensuring only authorized users can modify data. |
| NFR4 | The system shall encrypt user data for secure storage and transmission. |
| NFR5 | The system shall restrict administrative functions to authorized personnel only. |

### Usability Requirements
| ID   | Requirement |
| :---:| :---------------------------------------------------------------------------------------------------------------------- |
| NFR6 | The system shall provide an intuitive interface, enabling easy interaction with features and information. |
| NFR7 | The system shall ensure smooth and intuitive navigation between different website pages, minimizing load times and enhancing user flow. |
| NFR8 | The system shall maintain consistent branding and design across all website elements, from the homepage to individual product pages, to ensure a cohesive user experience. |
| NFR9 | The system shall immediately update the shopping cart icon to reflect the correct number of items when a product is added, ensuring real-time accuracy. |
| NFR10| The system shall be designed with responsive elements for optimal usability and layout on various devices, including desktops, tablets, and smartphones. |

### Compatibility Requirements
| ID   | Requirement |
| :---:| :------------------------------------------------------------------------------------------------------------------------- |
| NFR16| The system shall maintain consistent and error-free data across all user interactions and transactions, preventing discrepancies or conflicts. |
| NFR17| The system shall ensure an uptime of 99.9%, guaranteeing constant accessibility for users. |
| NFR18| The system shall continuously update product information and pricing in real-time, syncing with the inventory management system for accuracy. |
| NFR19| The system shall persistently store user selections in the shopping cart across multiple sessions. |
| NFR20| The system shall provide immediate and clear confirmation messages or visual cues when users add, edit, or delete products, preventing unintentional data modifications. |

### Reliability Requirements
| ID   | Requirement |
| :---:| :------------------------------------------------------------------------------------------------------------------------- |
| NFR21| The system shall support a specified maximum number of concurrent users based on projected traffic without experiencing performance degradation. |
| NFR22| The system shall allow multiple users to retrieve and view their order summaries concurrently without losing performance. |
| NFR23| The system shall handle image uploads efficiently, resizing and compressing images within 2 seconds for web optimization without quality loss. |
| NFR24| The system shall display an error message to the admin within 1 second in cases of errors, such as incorrect credentials or server issues. |
| NFR25| The system shall ensure server response times are consistently quick enough for all user actions, ensuring swift backend data processing and a seamless experience. |

# Change management plan

## Integration Plan for E-commerce Shopping App

The goal of this Change Management plan is to seamlessly integrate our e-commerce shopping app into your business environment, ensuring a smooth transition for both administrators and users. The plan focuses on effective training strategies for users to utilize the app efficiently.

## Training Strategies

### User-Focused Training
- **Documentation**: Develop user-friendly manuals, video tutorials, and FAQs tailored for both administrators and regular users. These resources will cover all aspects of the shopping app, from product browsing to checkout and order history.
- **Administrator Mastery**: Administrators will undergo specialized training sessions focusing on product management and order handling. This includes actions such as adding, updating, and removing products, as well as managing orders effectively.
- **Knowledge Base**: Maintain a comprehensive knowledge base with troubleshooting guides and frequently asked questions. This will empower users to find solutions independently.

### Integration with Ecosystem/Software
- **Compatibility Assessment**: Conduct a thorough analysis of your current software and ecosystem to identify potential integration points and dependencies. Evaluate compatibility to ensure a smooth fit and minimal disruption.
- **API Documentation**: Provide detailed, accessible API documentation, outlining integration protocols and requirements. Offer support in interpreting and implementing APIs for a straightforward integration process.

### Issue Resolution
- **Issue Reporting Mechanism**: Implement a user-friendly and easily accessible issue reporting mechanism within the app.
- **Priority Classification**: Establish a priority classification system based on the severity and impact of reported issues.

---

This plan directly addresses the requirements for the integration of the new application in the customer's office environment. It considers the training of personnel, ensuring smooth integration with existing systems, and efficient resolution of any arising issues.


# Traceability links

## Use Case Diagram Traceability

| Artifact ID | Artifact Name        | Requirement ID              |
|-------------|----------------------|-----------------------------|
| User UseCase    | REGISTER             | FR2             |
| User UseCase    | LOGIN                | FR1             |
| User UseCase    | SEARCH PRODUCT       | FR17           |
| User UseCase    | ADD PRODUCT TO CART | FR18           |
| User UseCase    | REMOVE PRODUCT       | FR7           |
| User UseCase    | CHECKOUT             | FR10     |
| Admin UseCase    | Add product          | FR21           |
| Admin UseCase    | Update product       | FR24            |
| Admin UseCase    | Remove Product       | FR25            |
| Admin UseCase    | View / Check product | FR19           |



## Activity Diagram Traceability

| Artifact ID           | Artifact Name      | Requirement ID              |
|-----------------------|--------------------|-----------------------------|
| User Activity Diagram   | REGISTER           | FR2, NFR1, NFR6             |
| User Activity Diagram   | LOGIN              | FR1, NFR1, NFR6             |
| User Activity Diagram   | SEARCH PRODUCT     | FR17, NFR7, NFR10           |
| User Activity Diagram   | ADD PRODUCT        | FR18, NFR9, NFR10           |
| User Activity Diagram      | REMOVE PRODUCT     | FR7, NFR9, NFR10            |
| User Activity Diagram      | CHECKOUT           | FR10, NFR7, NFR9, NFR10     |
| Admin Activity Diagram  | Add product        | FR21, NFR1, NFR6            |
| Admin Activity Diagram  | Update product     | FR24, NFR1, NFR6            |
| Admin Activity Diagram  | Remove Product     | FR25, NFR1, NFR6            |
| Admin Activity Diagram  | View/Check product | FR19, NFR7, NFR10           |


## Class Diagram Traceability

| Artifact Name | Requirement ID                  |
|---------------|---------------------------------|
| Admin Player         | FR11-15-25, NFR5 |
| Customer  Player             | FR1-10, FR16-20, NFR6-10 |
| Product Player               | FR17-25, NFR13, NFR18 |
| Orders  Player               | FR9-14, NFR16-20 |

# Software Artifacts

<Describe the purpose of this section>

*[I am a link](to_some_file.pdf)
