# 🔍 Dev Detective Project

Dev Detective is a simple and interactive web application that allows users to search for any GitHub profile and view important details like repositories, followers, following, location, and account creation date.  
It uses the **GitHub Users API** to fetch real-time data.

🚀 **Live Demo:**  
👉 https://abhidwi1.github.io/Dev-Detective-Project/

---

## 📸 Preview

[Dev Detective Preview](./screenshots/preview.png)  

---

## ✨ Features

- 🔎 Search GitHub users by username  
- 👤 Displays profile image, name, and username  
- 📊 Shows number of repositories, followers, and following  
- 📍 Displays location (if available)  
- 📅 Shows GitHub join date  
- 🌗 Light / Dark mode toggle  
- ❌ Handles invalid usernames gracefully  

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**
- **GitHub REST API**

---

## 📂 Project Structure

Dev-Detective-Project/
│
├── index.html
├── style.css
├── script.js
├── assets/
│   └── images/
│       └── avatar.png
└── README.md
## 📄 Project Explanation

### 🔹 index.html
This is the main entry point of the application.  
It defines the structure of the web page including:

- 🔍 Search input field for GitHub username  
- 🔘 Search button  
- 👤 Profile card layout  
- 📊 Sections for user information (repositories, followers, following, location, join date)  
- 🌗 Theme toggle (Light / Dark mode)  

The HTML is kept clean and semantic for better readability and accessibility.

---

### 🎨 style.css
This file is responsible for the complete UI design of the project.  
It includes:

- 📱 Responsive layout design  
- 🌙 Dark and ☀️ Light theme styling  
- 🧩 Card-based UI for profile display  
- ✨ Smooth transitions and hover effects  
- 🎯 Proper spacing, fonts, and colors for a modern UI look  

CSS variables are used to easily switch between light and dark themes.

---

### ⚙️ script.js
This file contains all the core logic of the application.

**Main responsibilities:**

- ⌨️ Capturing user input from the search bar  
- 🌐 Fetching GitHub user data using GitHub REST API  
- ⚠️ Handling API responses and errors  
- 🔄 Dynamically updating the UI with fetched data  
- 🌗 Managing light/dark mode toggle  
- 🚫 Handling cases where user data is not available  

This file makes the application interactive and dynamic.

---

### 📁 assets/
This folder contains static resources used in the project.

#### ▸ images/
Stores images such as:
- 👤 Default avatar image  
- 🖼️ Icons or UI-related images 

---

### 📘 README.md
This file provides complete documentation of the project including:

- 📝 Project description  
- ✨ Features  
- 🛠️ Tech stack  
- 📂 Project structure  
- 🚀 Usage instructions  

It helps recruiters and other developers understand the project quickly.

---

## 🔄 Application Flow

1. User enters a GitHub username in the search bar  
2. Clicks the search button or presses **Enter**  
3. JavaScript sends a request to the GitHub Users API  
4. API returns the user data  
5. UI updates dynamically with profile details  
6. If the username is invalid, an error message is displayed  

---

## 💡 Key Learnings from This Project

- 🌐 Working with REST APIs  
- ⚡ Fetch API and `async/await`  
- 🧠 DOM manipulation using JavaScript  
- ⚠️ Error handling in API calls  
- 🌗 Implementing dark/light mode  
- 📱 Building responsive and user-friendly UI  

---


