# Online Book Store - Spring Boot Application

A comprehensive e-commerce platform for book enthusiasts, built with Java and Spring Boot. This project stands out by implementing its own **custom data structures** and **file-based persistence system**, demonstrating core computer science concepts integrated into a modern web framework.

## 🚀 Features

### For Users:
- **User Authentication:** Secure registration and login system.
- **Book Catalog:** Browse books by category or view featured titles.
- **Shopping Cart:** Add/remove items and manage quantities seamlessly.
- **Payment Management:** Securely save and manage payment cards for faster checkout.
- **Order Processing:** Integrated checkout system with simulated payment processing.
- **Reviews & Ratings:** Share feedback on books with a dedicated review system.
- **Profile Management:** Update personal information and view saved preferences.

### For Admins:
- **Dashboard:** Overview of the store's performance.
- **Inventory Management:** Full CRUD operations for books (Add, Update, Delete).
- **User Management:** Monitor and manage registered users.

## 🛠️ Technical Highlights

- **Custom Data Management:** Instead of standard collection libraries, the project utilizes a **custom-built Linked List (`LinkedListUtil`)** for in-memory data handling, showcasing efficient data manipulation.
- **File-Based Persistence:** No external database required! The application uses a custom **text-based storage system** with pipe-delimited data persistence, making it highly portable and easy to set up.
- **RESTful Architecture:** Clean separation of concerns with a robust API layer handling communication between the frontend and service layers.
- **Dynamic Frontend:** A responsive user interface built with HTML5, CSS3, and JavaScript, served directly via Spring Boot.

## 💻 Tech Stack

- **Backend:** Java 21, Spring Boot 3.5.x
- **Build Tool:** Maven
- **Frontend:** HTML5, CSS3, JavaScript
- **Storage:** Custom File-based System (.txt)

## 📂 Project Structure

```text
onlinebookstore/
├── src/main/java/com/bookstore/onlinebookstore/
│   ├── controller/   # API Endpoints
│   ├── service/      # Business Logic
│   ├── repository/   # Custom File-based Data Access
│   ├── model/        # Data Entities
│   ├── util/         # Custom Data Structures (Linked List) & File Handlers
│   └── dto/          # Data Transfer Objects
├── src/main/resources/
│   ├── static/       # Frontend Assets (HTML, CSS, JS, Images)
│   └── data/         # Text-based Database Files
└── pom.xml           # Project Dependencies
```

## ⚙️ Getting Started

### Prerequisites
- **Java 21** or higher
- **Maven** (or use the included wrapper)

### Installation & Running

1. **Clone the repository:**
   ```bash
   git clone https://github.com/JKPLakshithaDilshan/Online-Book-Store-SpringBoot.git
   cd Online-Book-Store-SpringBoot
   ```

2. **Build the project:**
   ```bash
   ./mvnw clean install
   ```

3. **Run the application:**
   ```bash
   ./mvnw spring-boot:run
   ```

4. **Access the store:**
   Open your browser and navigate to `http://localhost:8080`
