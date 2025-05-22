# 📚 BookStore API Automation Project

This project automates REST API testing for a BookStore application using Java, RestAssured, TestNG, Cucumber, and Allure Reports for reporting.

---

## 🚀 Tech Stack

- **Java 21**
- **Maven**
- **TestNG**
- **RestAssured**
- **Cucumber**
- **Allure Reports**

---

## 📁 Project Structure

├── src/
│ ├── test/
│ │ ├── java/
│ │ │ ├── Steps/ # Step definitions
│ │ │ ├── Hooks/ # Hooks (Before/After)
│ │ │ └── Runner/ # Test Runner
│ └── resources/
│ └── features/ # Gherkin feature files
├── pom.xml # Maven dependencies
└── README.md # Project info


---

## ⚙️ Prerequisites

- Java 21 installed and added to PATH
- Maven installed and added to PATH
- [Allure Commandline](https://docs.qameta.io/allure/#_installing_a_commandline) (Optional for local report viewing)

---

## 🧪 How to set up and  Run Tests

1) Create a new maven project for automation or clone from the github if already present
2) Fork the Dev repo given and make it up in the local machine , to run the automation (The steps will be present in README.md of Dev repo)
3) End Points automated covered in this automation are:

    * POST /signup – To sign up to the book store
    * POST /login – To login after sign up and generate a token
    * POST /books – Create a new book
    * PUT /books/{id} – Update an existing book
    * GET /books/{id} – Fetch a book by ID
    * GET /books – Fetch all books
    * DELETE /books/{id} – Delete a book

6) Execute the automation suite by running the Cucumber Runner. This will trigger all feature scenarios written in a human-readable format, ensuring comprehensive test coverage and clear visibility into the executed test cases.
7) Once done , Allure- reports will be generate and can be seen under target/allure-results


