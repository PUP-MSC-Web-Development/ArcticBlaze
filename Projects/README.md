FRONTEND

Project 1:
Concept - Fan Website (Showcase something or someone you love! A pet, an idol, a group, etc)
Requirements:
Media Queries for responsiveness across different screen sizes.
CSS Variables for easy theme customization (e.g., colors, fonts).
Use of Web Fonts (e.g., Google Fonts) for typography.
Image Optimization for faster loading times.

Project 2:
Concept - Magazine Website
Requirements:
Responsive Typography that scales based on screen size.
CSS Transitions for smooth hover and interactive effects.
CSS Grid to create complex magazine-like layouts (e.g., articles with images, headers, etc.).
Lazy Loading for images to improve page performance.
Use of JavaScript to create a carousel or slideshow for featured content.

Project 3:
Concept - E-commerce Website
Requirements:
Form Validation using JavaScript for the pretend checkout process.
Local Storage to store items in a mock shopping cart.
Event Listeners for dynamic interactivity (e.g., add to cart buttons, quantity adjustments).
Filter and Search Functionality to browse products

Project 4:
Concept - “My Professional Portfolio”
Requirements:
CSS Keyframe Animations for elements like intro sections or skill bars.
Scroll-triggered Animations using JavaScript (e.g., reveal sections as the user scrolls).
Custom Cursor Effects for a more personal touch.
Interactive Navigation Menu with smooth scrolling to sections.
Media Integration (e.g., embedded videos, images) to showcase projects.












BACKEND

Project 1: Web-Based To-Do List Application
Back-End Concept: Simple Task Management System (CRUD Operations)
Requirements:
Basic CRUD Operations:
Create: Implement a POST request to add new tasks with fields for title and description. Users can submit a form with the task details.
Read: Implement a GET request to fetch all tasks from the database and display them in a list format. Each task should show its title and description.
Update: Implement a PUT request that allows users to edit an existing task's title or description. Users can select a task to modify and submit the changes through a form.
Delete: Implement a DELETE request to remove tasks from the database. Provide a button for users to delete a task from the list.

Database Setup: 
Use a simple database like SQLite or JSON files to store tasks. 
Each task can have fields: id, title, and description.

Learning Focus: Understanding how to create and interact with a RESTful API. Basic CRUD operations and their implementation in a web application. Simple front-end and back-end integration without complex features.



E-Commerce Website Project for Back-End Team

Project 2
Phase 1: User Registration Functionality
Back-End Concept: Basic User Authentication
Requirements:
User Registration: Implement a simple registration form where users can create an account (name, email, password).
Password Hashing: Use a basic password hashing library like bcrypt for securely storing passwords.
User Login: Implement a login system where users can sign in with their email and password.
Session Management: Use session cookies (to avoid complexity of JWT) to maintain user login state.
Basic Validation: Ensure simple validation for email format and password length.
Learning Focus: Basic user authentication, password security, and session handling without complex token management.


Project 3 
Phase 2: Product Feedback Functionality
Back-End Concept: Simple Review System with Media Upload
Requirements:
Feedback API: Allow users to leave a text review and star rating (1-5) for a product.
Image Upload: Implement image upload functionality using simple local file storage (e.g., store images in a server folder) or free cloud storage like Cloudinary for hosting images.
Basic Rating System: Users can submit a star rating, which is saved to the database.
Pagination: Implement basic pagination for the product review list, making sure users can browse reviews easily.
Learning Focus: File upload basics, handling media uploads, and simple CRUD operations for managing reviews.

Project 4
Phase 3: Cart & Checkout Functionality
Back-End Concept: Basic Cart Management
Requirements:
Cart API: Allow users to add products to their cart, update quantities, and remove items.
Local Storage: For simplicity, store cart information in the user’s local storage so it persists between sessions (without needing user authentication).
Checkout Form: Build a simple checkout form where users can input their shipping information (no payment integration needed at this point).
Basic Order Summary: After the checkout, show users a summary of their order (products, quantities, and total cost).
Learning Focus: Handling cart data in local storage, basic order processing, and managing cart logic.

Project 5
Phase 4: Fully Functioning E-commerce Website
Back-End Concept: Simple E-commerce Backend
Requirements:
Product Management API: Build a simple API for adding, updating, and removing products. This can be done through an admin panel where admins (hardcoded users) can manage products.
Simple Search and Filtering: Allow users to search for products by name or filter by category (no complex algorithms needed).
Authentication for Admin Users: Implement a basic admin login system where specific users (predefined) can manage the products and orders.
Basic Security Measures: Introduce simple validation to prevent common security vulnerabilities (e.g., SQL injection) and secure password storage.
Simplified Stock Management: As products are purchased, reduce stock quantities accordingly.

