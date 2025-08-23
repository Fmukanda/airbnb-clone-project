# airbnb-clone-project
Welcome to the **Airbnb Clone Project** repository! 🚀 
***
## Frontend Project
> ###  Overview
This project is a full-stack clone of the popular accommodation booking platform AirBnB. The goal is to build a functional web application that allows users to browse property listings, view detailed property information, and complete bookings. The project will cover frontend development, backend APIs, database design, and deployment.
> ### Project Goal 
To develop a functional web application that allow user to browse property listings, view detailed property information, and complete bookings.
> ### Tech Stack
 - **Frontend:** HTML, CSS, JavaScript, and React
 - **Version Control:** Git and GitHub
 - **Design Tools:** Figma for UI/UX design
> ### UI/UX Design Planning
 1. **Design Goals**
     - Create intuitive booking flow
     - Maintain visual consistency
     - Ensure fast loading times
     - Prioritize mobile responsiveness
 2. **Key Features**
     - Property search and filtering
     - Detailed property viewing
     - Secure checkout process
     - User authentication
 3. **Primary Pages**
    |Page| Description |
    |:----| :---------- |
    |Property Listing View| Grid display of available properties with filters      |
    |Listing Detailed View| Complete property details with images and booking form |
    |Simple Checkout View | Streamlined payment and booking confirmation           |
  4. **User-Friendly Design**                                                                                                                                               
      - A well-designed booking system reduces friction in the user journey, increases conversion rates, and improves customer satisfaction.
      - Clear navigation, intuitive interfaces, and responsive design are critical for success.                 -      
  5. **Color Styles**
     - Primary: #FF5A5F
     - Secondary: #008489
     - Background: #FFFFFF
     - Text: #222222
     - Secondary Text: #717171
   6. **Typography**
      - Primary Font: Circular, Medium (500), 16px
      - Headings: Circular, Bold (700), 24px-32px
      - Secondary Text: Circular, Book (400), 14px
 > ### Project Roles and Responsibilities
  |        Role        |          Responsibilities                                          |
  |:------------------ | :------------------------------------------------------------------|
  |Product Owner       | Defines requirements, prioritizes features, represents stakeholders|
  |Designers           | Creates mockups, maintains design system, ensures UX quality       |
  |Frontend Developers | Implements UI components, ensures responsive design                |
  |Backend Developers  | Builds APIs, manages database, implements business logic           |
  |QA/Testers          | Writes test cases, performs testing, reports bugs                  |
  |DevOps Engineers    | Manages deployment, CI/CD pipeline, server infrastructure          |

   > ### UI Component Patterns 
  1. **Navbar**
     - Logo
     - Search bar
     - User navigation
     - Responsive menu
 2. **Property Card**
     - Property image
     - Basic details (price, location, rating)
     - Favorite button
     - Responsive layout
 3. **Footer**
     - Site links
     - Company information
     - Social media links
     - Copyright information
   
    Each component will be designed for reusability and consistency across the application.

## Backend Project
> ### Overview
This project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. 
> ### Project Goal
To build a scalable web application (using Django, PostgreSQL, and GraphQL) that is designed to clone the robust booking platform of Airbnb.
> ### Team Roles
  |        Role             |          Responsibilities                                                 |
  |:------------------      | :-------------------------------------------------------------------------|
  |Project Manager          | Oversees timeline, coordinates team, manages deliverables                 |
  |Software architect       | Design software architectures by implementing product vision              |
  |Database Administrator   | Design, implements and maintains database systems                         |
  |Backend Developers       | Builds APIs, manages database, implements business logic                  |
  |Test automation engineer | Designs a test automation ecosystem by writing and maintaing text scripts |
  |DevOps Engineers         | Manages deployment, CI/CD pipeline, server infrastructure                 |
 > ### Technology Stack
  - **Django:** a web framework for building RESTful APIs.
  - **PostgreSQL:** a relation database management system.
  - **GraphQL:** a query language and server-side runtime for APIs.
 > ### Database Design
  **Key Entities and Fields**
  - **Users:** User Id, first name, last name, email address, Address
  - **Bookings:** Booking Id, Property Id, Check in date, Check out date, number of guest
  - **Reviews:** Review Id, Property Id, Booking Id, Rating, Reviewer Id  
  - **Payments:** Payment Id, Amount, Currency, Payment Type, Payment Status
    
  **Entities Relationship**
   - One user can have many properties
   - One Reviewer can have many reviews
   - One payment can belong to one booking
   - One property can have many bookings

 > ### Feature Breakdown
  - **User Management:** This feature manage users accounts. It enables addition, allocation of roles, grouping, and removal of users from system.
  - **Broperty management:** This feature manage the onboarding of properties to the system. It enables addition, tracking, and removal of properties from system.
  - **Booking system:** This feature manage the onboarding of customers to the system. It enable customer to search for propert and make reservation.
  - **Payment gateway:** This feature streamlined payment process through third party APIs. It links customer payments to property owner's bank account.
 > ### API Security
  - **Authentication,:** Authentication validates the identity of the client through user name and password. This wil be achieved through Basic Auth and API Key Authentication.
  - **Authorization:** Authorization determines the level of user access to system resources once they pass the authentication process. This will be achieved through assignement of user roles, permission, and rules.
  - **Rate limiting:** Rate limitiing are security policies and procedures within the property management system which will ensure the integrity of the business process. This will be achieved through impementing business rules within the application logic.

    **Security is crucial in the following key areas:**
    -  **Protecting user data:** This ensure the privacy, integrity, and the right use of the user data are observed within the law guidelines and best practice framework.
    -  **Securing payments:** This ensures that only aouthorized and approved payments are process. It protects fraudulent activities by unauthorized users.  
 > ### CI/CD Pipeline
   CI/CD pipelines are the automated processes in software development, testing, and deployment. 
   CI/CD pipelines are important in the software development cycle because it ensure continiues integration software features, faster deploymnet of application, flexibilty, and agility in software development.
   The following CI/CD tools will be used in this project
   + Docker
   + GitHub Actions
   + Jenkins
   + Ansible

