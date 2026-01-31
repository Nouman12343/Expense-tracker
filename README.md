Expense Tracker (Full Stack)

A simple, modern expense tracker built with a Java (Spring Boot) backend and a Vanilla HTML/CSS/JavaScript frontend using Tailwind CSS.

How It Works

Frontend: A sleek web interface for adding, viewing, and deleting transactions.

Backend: A Java REST API that stores your data (currently in-memory for easy setup).

Hybrid Mode: If the Java backend is not running, the app automatically switches to Local Storage so your data isn’t lost.

Required Libraries & Tools

No manual installation needed—libraries are handled via CDN and Maven.

Frontend (CDN)

Tailwind CSS — Modern, responsive styling

FontAwesome — Icons for UI

Inter Font — From Google Fonts

Backend (Java Environment)

Java 17+ — Required to run the Spring Boot application

Maven — For dependency management and building

How to Run the Project

Start the Backend

Open the project in VS Code.

Navigate to src/expensetracker/ExpenseBackend.java.

Click the Run button above the main method.

The server will start at http://localhost:8080
.

Open the Frontend

Open index.html in any web browser.

A green "Java Backend" indicator will appear in the top-right corner if the backend is connected.

Project Structure (Simplified)

index.html — Main web interface

script.js — Frontend logic and API communication

style.css — Custom styles, scrollbar, and fonts

pom.xml — Maven configuration and dependencies

src/expensetracker/ — Java backend source files

target/classes/expensetracker/ — Compiled backend classes
