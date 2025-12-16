# ☕ Coffee Lane: Full-Stack E-commerce Platform (still in progress)

<br> <img width="1880" height="954" alt="image" src="https://github.com/user-attachments/assets/aba2ffaf-143e-401f-a10e-46a268bed170" />

<br> Link to Live Site: https://coffelaneshop.vercel.app/ _(please keep in mind - this is a free project and the link can become unavailable any moment)_

🌟 Project Context & Goal
This was a non-commercial pet project created to showcase robust full-stack development skills within a realistic e-commerce environment. The primary goal was to successfully simulate the real-life process of software development, team collaboration, and full system deployment, resulting in a fully functional online shop.

<br> <img width="1891" height="950" alt="image" src="https://github.com/user-attachments/assets/ff2047be-a6fc-48c5-8a49-c8a4330ba50b" />

<br> ✨ Key Features
1. Comprehensive Full-Cycle Management
This platform is built for end-to-end functionality, demonstrating proficiency in handling both user-facing interactions and backend management.

Shopping Cart & Checkout: Standard e-commerce functionality for browsing products, managing a cart, and simulating the order process.

User Authentication & Security: Implementation of secure login, registration, and user session management, relying on JWT/OAuth2 for token-based authorization.

<br> <img width="1913" height="953" alt="image" src="https://github.com/user-attachments/assets/e0458ad6-6db3-4cc1-a245-1850d8385d9b" />

<br> 2. Dedicated Administration Panel
A critical feature of this project is the fully functional administration interface, which allows site operators to manage content, products, and users effectively. This demonstrates the ability to build and secure complex B2B (business-to-business) functionality for system operation.

<br> 🛠️ Technology Stack Deep Dive
The architecture is modern and comprehensive, built for performance and maintainability across both the client and server.

Frontend Technologies (User Interface)
The client-side uses the React and JavaScript ecosystem for a dynamic user experience. State management is handled by Redux Toolkit for centralized and predictable application state. The UI is built with Material UI for standardized, professional components, and routing is managed by React Router. API communication is handled via Axios, and authentication relies on JWT/OAuth2.

Backend & Logic (Python-based)
The server-side provides a scalable foundation built on Python and Django Rest Framework (DRF), used for building secure and maintainable RESTful APIs. Security is enforced using JWT/OAuth2.

Data persistence utilizes PostgreSQL, hosted via Supabase. The deployment architecture leverages Docker for containerization and Render for orchestration and hosting. Asynchronous operations, such as sending emails or processing data, are offloaded using Celery. The API is documented using DRF-yasg (Swagger), tested with Postman, and transactional emails are handled by Mailjet.
