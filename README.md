# Simple Qt Calculator

A basic calculator application built with C++ and the Qt framework. This project was created as an exercise to understand the fundamentals of creating a GUI application, handling user input, and managing layouts in Qt.

## 📸 Screenshot

<img width="268" height="221" alt="image" src="https://github.com/user-attachments/assets/40b57e51-e82c-4727-8030-06e646d2103f" />

---

### ✨ What this Project Demonstrates

*   **GUI Layout Management:** The user interface is built programmatically using `QGridLayout` and `QHBoxLayout` to arrange widgets in a responsive grid.
*   **Widget Usage:** Makes use of standard Qt widgets like `QPushButton` for the number pad and `QSpinBox` for input and display.
*   **Event Handling with Signals & Slots:** The core logic is driven by Qt's powerful signals and slots mechanism.
*   **Modern C++ Syntax:** Uses C++11 lambda functions for connecting signals to slots, resulting in cleaner and more concise code.
*   **Basic State Management:** Implements simple logic to handle a two-term calculation (addition and multiplication) by storing the first term and the selected operation.

---

### 🛠️ Technologies Used

<div>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="Qt"/>
</div>

*   **C++** as the main programming language.
*   **Qt Framework (Widgets Module)** for the entire graphical user interface.
*   **Qt Creator / qmake** for project management and building.

---

### 🚀 How to Build and Run

**1. Prerequisites**
*   A C++ compiler (GCC, Clang, MSVC).
*   The Qt framework (version 5 or 6) must be installed on your system.

**2. Build Instructions**
*   Open a terminal in the project's root directory and use `qmake` and `Cmake` to build the application:
