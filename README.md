# 🏦 Bank Management System (C++ Console Application)

Welcome to the **Bank Management System** repository! This is a comprehensive, feature-rich console application built entirely in C++ using **Object-Oriented Programming (OOP)**, **Data Structures**, and **Clean Architecture** concepts.

---

## 🎯 About The Project & Learning Journey

This project is the culmination of my foundational learning journey in computer science and software development. It was built after completing the first 13 core courses from the **ProgrammingAdvices Roadmap** (by **Dr. Mohammed Abu-Hadhoud**), which covers fundamental programming concepts, advanced algorithms, object-oriented design, and data structures.

---

## 📚 Course Foundations Applied (Courses 01 - 13)

- **Programming Foundations (C++):** Memory management, control structures, and standard I/O.
- **Algorithms & Problem Solving (Levels 1 - 5):** Designing efficient algorithms, array manipulation, bitwise operations, and data validation.
- **Object-Oriented Programming (Levels 1 & 2):** Classes, Inheritance, Polymorphism, Encapsulation, Abstraction, and File Management.
- **Data Structures (Level 1):** Linked Lists, Stacks, Queues, and dynamic memory allocation.

---

## 📜 Course Certificates (Levels 5–13)

Click any certificate preview to open the full-size certificate image.

|                    Course Level                     |                                             Certificate Preview                                             |
| :-------------------------------------------------: | :---------------------------------------------------------------------------------------------------------: |
| **Level 5** — Algorithms & Problem Solving Level 2  |  [![Level 5 Certificate](Bank-Client/certificates/Level%205.png)](Bank-Client/certificates/Level%205.png)   |
|                     **Level 6**                     |  [![Level 6 Certificate](Bank-Client/certificates/Level%206.png)](Bank-Client/certificates/Level%206.png)   |
| **Level 7** — Algorithms & Problem Solving Level 3  |  [![Level 7 Certificate](Bank-Client/certificates/Level%207.png)](Bank-Client/certificates/Level%207.png)   |
| **Level 8** — Algorithms & Problem Solving Level 4  |  [![Level 8 Certificate](Bank-Client/certificates/Level%208.png)](Bank-Client/certificates/Level%208.png)   |
|          **Level 9** — Foundations Level 2          |  [![Level 9 Certificate](Bank-Client/certificates/Level%209.png)](Bank-Client/certificates/Level%209.png)   |
|             **Level 10** — OOP Concepts             | [![Level 10 Certificate](Bank-Client/certificates/Level%2010.png)](Bank-Client/certificates/Level%2010.png) |
|           **Level 11** — OOP Applications           | [![Level 11 Certificate](Bank-Client/certificates/Level%2011.png)](Bank-Client/certificates/Level%2011.png) |
|       **Level 12** — Data Structures Level 1        | [![Level 12 Certificate](Bank-Client/certificates/Level%2012.png)](Bank-Client/certificates/Level%2012.png) |
| **Level 13** — Algorithms & Problem Solving Level 5 | [![Level 13 Certificate](Bank-Client/certificates/Level%2013.png)](Bank-Client/certificates/Level%2013.png) |

---

## 🚀 Key Features

---

## 💡 Security Lesson Learned (A Note from the Author)

> **Plain Text Password Storage:** During the development phase of this console project (as part of my foundational learning), user passwords were initially stored in plain text within text files.
>
> Through this project, I realized the critical security risks associated with unencrypted storage (lack of confidentiality and vulnerability to data breaches). This became a core milestone for my growth, and in my upcoming enterprise/backend projects (ASP.NET Core & Database levels), I am strictly implementing modern security standards, including **Password Hashing (BCrypt/Argon2)** and **JWT Authentication**.

### 🔐 1. Authentication & Role-Based Access Control (RBAC)

- **User Login:** Secure authentication with username and password verification.
- **Bitwise Permissions System:** Flexible permission flags granted per user to restrict or allow access to specific system features.
- **Access Guard Screen:** Rejects unauthorized feature execution with clear visual feedback.

### 💼 2. Client Management (CRUD Operations)

- **View Clients List:** Formatted tabular display of client accounts and balance details.
- **Add New Client:** Interactive prompts with uniqueness validation for Account Numbers.
- **Update / Delete Client:** Modify client records or remove them safely with confirmation checks.
- **Find Client:** Instant client lookup by account number.

### 💸 3. Financial Transactions & Validations

- **Deposit & Withdraw:** Secure balance adjustments with built-in validation (e.g., handling insufficient balance scenarios).
- **Account Transfer:** Transfer money directly between two accounts with real-time balance updates for both parties.
- **Transfer Audit Logs:** Automatically logs every transfer operation with timestamp, source account, destination account, transferred amount, and executing user.

### 💱 4. Multi-Currency Exchange Engine

- **Currencies List:** Displays exchange rates for over 200 world currencies relative to USD.
- **Currency Lookup:** Search currencies by Country Name or Currency Code.
- **Currency Exchange Calculator:** Real-time conversion calculation between any two currencies using base USD exchange rates.

---

## 📸 Application Screenshots

### 1. Authentication & Main Menu

|                       Login Screen                       |                   Main Menu Screen                   |
| :------------------------------------------------------: | :--------------------------------------------------: |
| ![Login Screen](Bank-Client/ScreenShots/LoginScreen.png) | ![Main Menu](Bank-Client/ScreenShots/MainScreen.png) |

### 2. Client Management (CRUD)

|                         Client List                          |                        Add New Client                         |
| :----------------------------------------------------------: | :-----------------------------------------------------------: |
| ![Client List](Bank-Client/ScreenShots/ClientListScreen.png) | ![Add Client](Bank-Client/ScreenShots/AddNewClientScreen.png) |

|                      Update Client Details                       |                    Delete Client Confirmation                    |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: |
| ![Update Client](Bank-Client/ScreenShots/UpdateClientScreen.png) | ![Delete Client](Bank-Client/ScreenShots/DeleteClientScreen.png) |

### 3. Financial Transactions & Transfer Audit Logs

|                  Transfer Money Screen                  |                     Transfer Audit Logs Screen                     |
| :-----------------------------------------------------: | :----------------------------------------------------------------: |
| ![Transfer](Bank-Client/ScreenShots/TransferScreen.png) | ![Transfer Log](Bank-Client/ScreenShots/TransferLogListScreen.png) |

|                   Deposit Operation                   |                    Access Denied Guard                     |
| :---------------------------------------------------: | :--------------------------------------------------------: |
| ![Deposit](Bank-Client/ScreenShots/DepositScreen.png) | ![Access Denied](Bank-Client/ScreenShots/DeniedScreen.png) |

### 4. Currency Exchange Engine

|                         Currencies List                         |                          Find Currency                           |                      Currency Calculator                      |
| :-------------------------------------------------------------: | :--------------------------------------------------------------: | :-----------------------------------------------------------: |
| ![Currencies](Bank-Client/ScreenShots/CurrenciesListScreen.png) | ![Find Currency](Bank-Client/ScreenShots/FindCurrencyScreen.png) | ![Exchange](Bank-Client/ScreenShots/UpdateCurrencyScreen.png) |

---

## 🛠️ Tech Stack & Concepts

- **Language:** C++
- **Paradigm:** Object-Oriented Programming (OOP)
- **Data Persistence:** File I/O (Storing/Retrieving client, user, and currency records)
- **Architecture:** Tiered Architecture (UI Screens, Business Layer, Data Access Layer)

---

## 👤 Author

Developed with passion as part of my continuous learning journey towards becoming a Full-Stack / Backend Developer!

- **Roadmap:** [ProgrammingAdvices.com](https://programmingadvices.com/) (Dr. Mohammed Abu-Hadhoud)
