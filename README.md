# HiFi Horizon – Project Overview

This project was developed as part of a team assignment at Roskilde Tekniske Skole.

Within the web application **HiFi Horizon**, I was responsible for designing and implementing several key features across both frontend and backend. The sections below highlight my contributions and demonstrate my skills in React development, API integration, and backend services.

Here i have a link to the mail service repository from GitHub
[mail service api](https://github.com/DenisseDaugaard/HIFI__mail)
---

## Key Contributions

### API Integration
- Implemented API communication for authentication and related services  
  → [authService.js](./src/api/authService.js)

---

### Backend Email Service (Deployed on Render)
- Developed and deployed a Node.js/Express backend service on Render to handle contact form submissions
- Implemented a secure email flow using the **Resend API**
- Configured environment variables for secure API key handling
- Enabled real-time email delivery from the website contact form to a personal Gmail account
- Designed validation and error handling for incoming requests

**Key features:**
- REST endpoint: `/send-email`
- Input validation (name, email, subject, message)
- Email forwarding with reply-to functionality
- CORS and JSON middleware setup

---

### Contact Page
- Developed the contact page and integrated it with the backend email service
- Implemented form handling, validation, and user feedback flow
  - [Contact Action](./src/pages/ContactPage/action.js)
  - [Contact Component](./src/pages/ContactPage/Contact.jsx)
  - [Styling](./src/pages/ContactPage/contact.scss)
  - [Thank You / Redirect Page](./src/pages/ContactPage/Thanks.jsx)

---

### Authentication (Login)
- Built the login interface, including form validation and user interaction
  - [Login Page](./src/pages/Login/Login.jsx/)
  - [Login Styling](./src/pages/Login/Login.scss)
  - [Login Form & Logic](./src/pages/Login/LoginForm.jsx)

---

### User Registration
- Designed and implemented the account creation flow, including form handling and success feedback
  - [Create Account Page](./src/pages/CreateAccount/CreateAccount.jsx)
  - [Styling](./src/pages/CreateAccount/CreateAccount.scss)
  - [Form & Logic](./src/pages/CreateAccount/CreateAccountForm.jsx)
  - [Success Response Page](./src/pages/CreateAccount/SuccessfulRegistration.jsx)

---

### Payment Flow
- Developed a multi-step payment interface with clear user flow and structured components
  - [Payment Page](./src/pages/PaymentPage/PaymentPage.jsx)
  - [Payment Information](./src/pages/PaymentPage/PaymentInfo.jsx)
  - [Payment Method Selection](./src/pages/PaymentPage/PaymentMethod.jsx)
  - [Styling](./src/pages/PaymentPage/PaymentPage.scss)

---

### User Profile
- Implemented user profile management features, including editing and displaying user data
  - [Profile Page](./src/pages/Profile/Profile.jsx)
  - [Edit Profile](./src/pages/Profile/EditProfile.jsx)
  - [Profile Information](./src/pages/Profile/MyProfileInfo.jsx)
  - [Styling](./src/pages/Profile/Profile.scss)

---

## Summary

This project demonstrates my ability to:
- Build structured and reusable React components
- Integrate and manage API requests
- Develop full-stack features (frontend + backend)
- Deploy backend services using Render
- Handle real-world functionality such as email delivery
- Apply consistent styling using SCSS
- Work effectively within a team-based development environment.
