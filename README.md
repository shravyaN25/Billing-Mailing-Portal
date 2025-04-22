# 🏘️Annapurna Badavane Association - Billing Management Portal

## 🏡 About

The Annapurna Badavane Association Billing Portal is a full-stack Progressive web application (PWA) designed to automate and streamline the monthly maintenance fee collection process for the Annapurna Badavane residential colony. This application replaces the traditional manual bill writing and distribution system with a modern, efficient digital solution.

> *Note:* Since this codebase contains sensitive information about residents of Annapurna Badavane colony, the repository and deployment link are private and only accessible to authorized administrators.



## 💻 Purpose

Prior to this application, the colony administration faced significant challenges:

- Manual creation of maintenance bills was time-consuming (3+ days per month)
- Tracking payments and maintaining records was error-prone
- Distributing physical bills to all residents was logistically difficult
- Lack of transparency in financial reporting created trust issues


This application solves these real-world problems by providing a centralized system for resident management, automated bill generation, and digital distribution, significantly reducing administrative overhead while improving collection rates and financial transparency.

## 🌟 Features

### 🔒 Authentication & Security

- Secure admin login with environment variable-based credential management
- Multi-layered security with server-side validation, middleware protection, and secure cookie handling
- Protection against unauthorized access to sensitive resident and financial data


### 👫 Resident Management

- Add, edit, and remove resident information
- Store essential details including name, flat number, email, and contact information
- Search and filter capabilities for quick access to resident records


### 📃 Automated Billing

- Generate monthly maintenance bills for all residents with a single click
- Customize bill amounts for individual residents when needed
- Preview bills before sending to ensure accuracy
- Bulk generation option for efficient processing


### 📧 Email Notifications

- Automatically send professional-looking bills directly to residents' email addresses
- Email delivery status tracking to ensure bills reach recipients
- Customizable email templates with colony branding


### 💰 Payment Tracking

- Mark bills as "Paid" or "Pending" to track payment status
- Filter and view payment history by month, year, or resident
- Generate reports on collection rates and outstanding payments




## 👩‍💻 Tech Stack

- *Frontend*: React, Next.js, TypeScript, Tailwind CSS
- *Backend*: Next.js API Routes, Server Components, Server Actions
- *Database*: MongoDB
- *Authentication*: Custom JWT-based authentication with secure cookies
- *Email Service*: Nodemailer
- *Styling*: Tailwind CSS with shadcn/ui components
- *State Management*: React Hooks
- *Deployment*: Vercel


## 🌟 Application Structure

### 👩‍💻 Admin Login

- Secure authentication form with username/password validation
- Environment variable-based credential management for enhanced security
- JWT token generation and secure cookie storage
- Redirect to dashboard upon successful authentication


### 🔳 Dashboard Layout

- Responsive design that works on desktop and mobile devices
- Navigation between different sections (Residents, Generate Bills, Sent Bills)
- Logout functionality with proper session termination


### Dashboard Components

#### 📂 Residents Panel

- Complete CRUD operations for resident management
- Form validation for resident information
- Search and filter capabilities
- Confirmation dialogs for destructive actions


#### 📂 Generate Bills Panel

- Month and year selection for bill generation
- Default amount setting with individual overrides
- Resident selection for targeted billing
- Bill preview functionality
- Bulk generation with email delivery


#### 📂 Sent Bills Panel

- Comprehensive view of all sent bills
- Filtering by month, year, and payment status
- Payment status updates
- Bill preview functionality
- Search capability for finding specific bills

## 🔳 Screenshots

## Admin Login Page
![Image](https://github.com/user-attachments/assets/c0d22971-1d24-4410-a159-e86fbf34dcbd)

## Admin Dashboard 
![Image](https://github.com/user-attachments/assets/ecc49dca-df6c-4aec-a20b-a0b84b86f4c5)

## Residents Panel
![Image](https://github.com/user-attachments/assets/6316f6c5-6267-4c45-b787-bffe8265e7fd)

## Generate bills panel
![Image](https://github.com/user-attachments/assets/78805c4d-f2fb-42bc-bd08-b58d67a11093)

## Bill preview
![Image](https://github.com/user-attachments/assets/c47360a5-fd67-4625-96b4-083cad369b8c)

![Image](https://github.com/user-attachments/assets/d972a84d-2efe-41e8-8368-75f5005e53b7)

![Image](https://github.com/user-attachments/assets/e4fcd528-810a-4aa3-8b7d-76755b4db530)

![Image](https://github.com/user-attachments/assets/04870fe8-7aa0-4e36-b762-b4178829b3b8)

![Image](https://github.com/user-attachments/assets/54c6c207-4816-4351-a413-29d84b4563d6)

![Image](https://github.com/user-attachments/assets/5e68e877-4541-44b4-bc12-b8f743d91637)

![Image](https://github.com/user-attachments/assets/ff9363bc-e20a-4e8b-ad99-76fcad7bc125)

![Image](https://github.com/user-attachments/assets/1d22aae2-b128-402b-803c-632214e3ffd0)

## Unauthorized Access Protection
![Image](https://github.com/user-attachments/assets/851598e4-b001-46c3-b713-fb549c31f5a4)




## 🖥️ Impact and Results

Since implementation, this application has:

- Reduced administrative time from 3+ days to approximately 30 minutes per month
- Improved collection rates by approximately 35%
- Enhanced financial transparency and resident trust
- Eliminated paper waste from physical bills
- Provided better tracking and reporting of maintenance fee collection


## 🚀 Future Improvements

While the current version successfully addresses the core problems, future enhancements could include:

- Online payment integration
- Resident portal for self-service payment status checking
- Mobile app for administrators
- Advanced analytics and financial reporting
- Automated reminders for pending payments
- Multi-language support


---

Developed with ❤ by Shravya N for Annapurna Badavane Association
