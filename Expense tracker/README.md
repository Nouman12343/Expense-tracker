# 💰 Expense Tracker (Full Stack)

A simple, modern expense tracker built with a **Java (Spring Boot)** backend and a **Vanilla HTML/CSS/JavaScript** frontend with **Tailwind CSS**.

## 🚀 How It Works
1. **Frontend**: A sleek web interface where you can add, view, and delete transactions.
2. **Backend**: A Java REST API that stores your data (currently in-memory for easy setup).
3. **Hybrid Mode**: If the Java backend is not running, the app automatically switches to **Local Storage** so you don't lose your data!

---

## 🛠️ Required Libraries & Tools
You don't need to manually download libraries; the project handles them via CDN and Maven.

### Frontend (Included via CDN)
- **Tailwind CSS**: For modern, responsive styling.
- **FontAwesome**: For beautiful icons.
- **Inter Font**: From Google Fonts.

### Backend (Java Environment)
- **Java 17+**: Required to run the Spring Boot application.
- **Maven**: Used for dependency management and building.

---

## 🏃 How to Run the Project

### 1. Start the Backend
1. Open the project in VS Code.
2. Open [src/expensetracker/ExpenseBackend.java](src/expensetracker/ExpenseBackend.java).
3. Click the **"Run"** button that appears above the `main` method.
4. The server will start on `http://localhost:8080`.

### 2. Open the Frontend
1. Open [index.html](index.html) in any web browser.
2. You will see a green "Java Backend" indicator in the top right corner if it's connected correctly.

---

## 📁 Project Structure (Simplified)
- `index.html` — The main interface.
- `script.js` — App logic and API communication.
- `style.css` — Custom scrollbar and font styling.
- `pom.xml` — Project configuration and dependencies.
- `src/expensetracker/` — Java backend source files.
