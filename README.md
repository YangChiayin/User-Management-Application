# User Management Application
<img src="https://github.com/user-attachments/assets/e9221068-215e-46e4-83e8-3e88044c80e2" width="500" />

## Overview

This project demonstrates the concept of a **class library** in C#, focusing on managing user data through a `UserManager` class. The application allows the creation, management, and storage of user records (with properties like ID, username, password, and date of creation) and provides simple functionalities for handling phrases.

### Purpose

The goal of this project is to understand the functionality of a **class library** by encapsulating user management features into the `UserManager` class, which includes adding users, generating new IDs, and storing data in a file. Additionally, the project introduces handling simple text phrases using a `MainForm` Windows Forms application.

### Features

- **User Management**: 
  - Create and store user data, including ID, username, password, and the date the user was created.
  - Validate user input for username and password constraints.
  - Automatically generate a new ID based on existing records.

- **Phrase Management**:
  - Save user-inputted phrases and display them in reverse order in a `RichTextBox` control.
  - Filter out non-letter and non-digit characters from phrases before displaying them.

- **File Storage**:
  - Persist user records in a text file (`users.txt`) to simulate a simple database.

## Getting Started

### Prerequisites

To run this project, you will need the following:

- **Visual Studio** (Community Edition or any version that supports Windows Forms)
- **.NET Framework** (Compatible with your Visual Studio version)
- **C# knowledge** (Optional, but helpful for understanding the code)
