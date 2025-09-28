# Quiz API — ASE Challenge

## 📖 Project Description
The **Quiz API** is a lightweight backend service built with **TypeScript** and **Express**. It allows users to create quizzes, list them, fetch quiz details (without revealing answers), and attempt quizzes by submitting their responses to get a score. This project was designed as part of the **Associate Software Engineer Challenge** to demonstrate backend fundamentals, clean architecture, and test-driven development.

### ✨ Key Features
- **Create Quizzes** → Define a quiz with multiple-choice questions.
- **List Quizzes** → Retrieve all available quizzes with metadata.
- **Fetch Quiz by ID** → View quiz questions (without exposing correct answers).
- **Attempt a Quiz** → Submit answers and receive detailed scoring (total, correct answers, percentage).
- **In-Memory Store** → Keeps things simple for quick setup (no database dependency).
- **Test Suite** → Includes Jest tests for endpoints.

### 🛠️ Tech Stack
- **Node.js** + **Express** → Web framework
- **TypeScript** → Strong typing & maintainable code
- **Jest** + **Supertest** → Automated testing
- **UUID** → Unique IDs for quizzes and questions

### 📌 Why this project?
- Keeps scope realistic (4–6 hours of focused work).
- Demonstrates **API design**, **validation**, and **testing**.
- Clean modular structure: routes, controllers, models, and store.
- Clear documentation (README, examples, tests) to make it recruiter-friendly.

