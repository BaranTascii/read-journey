#  Read Journey

A modern reading tracker application that allows users to manage their reading journey, discover books, and track their progress in an intuitive and user-friendly interface.

---

##  Features

*  User authentication (Register / Login)
*  Personal library management
*  Recommended books system
*  Reading progress tracking
*  Book browsing and interaction
*  State management with Redux Toolkit
*  API integration for dynamic data
*  Fast and responsive UI

---

##  Tech Stack

### Frontend

* React
* Vite
* JavaScript (ES6+)
* CSS

### State Management

* Redux Toolkit

### API

* REST API (Axios / Fetch)

---

##  Project Structure

```bash
src/
 ├── components/     # Reusable UI components
 ├── pages/          # Application pages
 ├── redux/          # State management (auth & books)
 ├── utils/          # API & helper functions
 ├── main.jsx        # Entry point
```

---

##  Installation

```bash
git clone https://github.com/your-username/read-journey.git
cd read-journey
npm install
npm run dev
```

---

##  Authentication Flow

* Users can register and log in
* Protected routes prevent unauthorized access
* Authentication state is managed globally with Redux

---

##  State Management

Redux Toolkit is used for:

* Managing authentication state
* Handling book data
* Performing async API operations

---

##  API Integration

* Centralized API configuration
* Async requests handled via Redux operations
* Loading and error states managed properly

---

##  Purpose

This project was rebuilt from scratch to:

* Understand real-world React architecture
* Practice Redux Toolkit
* Learn scalable project structure
* Improve frontend development skills

---

##  Future Improvements

*  Mobile responsiveness
*  Notification system
*  Reading analytics

---

## 👨 Author

GitHub: https://github.com/BaranTascii

