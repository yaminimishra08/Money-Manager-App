# Capstone Project: Money Manager App 

## 📌 Project Overview

This project is a **personal finance management web application** built using **HTML5, CSS3, and JavaScript**.  
It allows users to **add, edit, and delete transactions**, categorize them as income or expense, and view a filtered, sorted summary of their finances. The project demonstrates practical implementation of **OOP concepts, dynamic DOM manipulation, and multi-page website structuring**.

---

## 🧱 Website Structure

The application contains the following pages:

### 1. Login Page (`login.html`)
* Users can **sign up** and **log in**.
* Validation ensures proper username and password format.
* Successful login redirects to the main transactions page.

### 2. Main Transactions Page (`index.html`)
* Add transactions with:
  - Amount
  - Date
  - Category (Income/Expense)
  - Sub-category
  - Description
* Form validation ensures correct and complete data.
* Edit functionality allows updating existing transactions.
* Transactions are stored in **localStorage** for persistence.

### 3. View Transactions Page (`transaction.html`)
* Displays all transactions in a table with:
  - Date
  - Category
  - Sub-category
  - Description
  - Amount
* Features:
  - Delete and edit buttons per transaction.
  - Filters by category, sub-category, and date range.
  - Sort options by date or amount.
* Shows a **summary of total income, expenses, and net balance**.

---

## 🎨 Styling & Design Approach
* Dark theme with clear contrast for readability.
* Consistent color scheme across pages.
* CSS uses **flexbox and responsive layouts** for proper spacing.
* Buttons, inputs, and tables styled for clarity and usability.
* Form validation highlights invalid input for better user experience.

---

## 📱 Responsiveness
The application adapts to various screen sizes using:
* Flexible layouts with proper padding and margins.
* Full-width forms and tables on mobile devices.
* Responsive buttons and input fields.

---

## 🌟 Key Features

- User authentication (signup/login)  
- Add, edit, and delete transactions  
- Filter by category, sub-category, and date range  
- Sort transactions by date or amount  
- Dynamic summary of income, expenses, and balance  
- Responsive design for desktop and mobile  

---

## 🔧 Future Enhancements

- Implement user-specific data (multiple users, private accounts)  
- Export transactions to CSV or PDF  
- Add charts/graphs for visual analysis of income vs expense  
- Dark/light theme toggle  
- Better error handling and notifications  

---

## 🗂 Repository Structure
```
login.html
index.html
transaction.html
style.css
transaction.css
README.md
.gitignore
```

* Each HTML file represents a page with a specific function.  
* CSS files handle styling for each page.  
* JavaScript is embedded in pages for dynamic functionality.  

The project follows the Git workflow:  
`dev` → `stage` → `main`

---

## 🚀 Technologies Used

* HTML5  
* CSS3  
* JavaScript (DOM Manipulation, Event Handling, OOP Concepts)  
* LocalStorage for data persistence  

---

## 📝 Project Report

**Implementation:**  
The project uses **JavaScript classes** to manage transactions. Users can dynamically add, edit, and delete transactions. Filtering and sorting allow a practical overview of finances. The pages are connected seamlessly, and data persists through **localStorage**, demonstrating a fully functional multi-page web application.

**Challenges Faced:**  
* Writing correct dynamic JavaScript logic initially caused multiple errors.  
* Linking multiple pages while keeping CSS and JS correctly applied was tricky.  
* Handling OOP concepts practically in a live web app was challenging at first.  
* Ensuring form validation and real-time updates for the table was complex.

**Key Learnings:**  
* Learned **how to implement OOP** in a web project and manipulate the DOM dynamically.  
* Gained experience building a **multi-page website** with consistent data handling.  
* Learned practical ways to connect HTML, CSS, and JS across multiple pages.  
* Improved debugging skills and understanding of localStorage for persistence.  

---

## 🌐 Live Demo
[Money Manager Live]()

---

## 🔗 Connect With Me
- LinkedIn: [www.linkedin.com/in/yaminimishra0804](https://www.linkedin.com/in/yaminimishra0804)  
- GitHub: [https://github.com/yaminimishra08](https://github.com/yaminimishra08)

---

## 📎 Submission
* This repository contains the **Capstone Money Manager Project** built using HTML, CSS, and JavaScript.  
* Demonstrates dynamic data handling, form validation, OOP implementation, and multi-page web development.  
* The project follows the Git workflow: `dev → stage → main`.
