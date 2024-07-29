# Cafe Management System

## Overview

The Cafe Management System is a Java-based application designed to help cafes manage their operations efficiently. It provides functionalities for booking orders, printing bills, changing the menu, and offering different access levels for administrators and regular users.

## Features

- **User Authentication**: Users can sign up, log in, and reset their passwords.
- **Order Management**: Place new orders and view order details.
- **Bill Management**: Print bills for completed orders.
- **Menu Management**: Add, edit, or delete menu items.
- **Category Management**: Manage product categories.
- **User Management**: Admins can verify users and manage security questions.
- **Security**: Change passwords and security questions for account safety.
- **Responsive UI**: The application is designed to work on screens with a resolution of 1920x1080.

## File Structure

The project consists of several Java and form files, each responsible for different functionalities:

### Java Files

- **AddNewProduct.java**: Logic for adding new products to the menu.
- **CafeManagementSystem.java**: Main class for the application.
- **ChangePassword.java**: Logic for changing user passwords.
- **ChangeSecurityQuestion.java**: Logic for changing security questions.
- **ForgotPassword.java**: Logic for handling forgotten passwords.
- **Home.java**: Main dashboard logic after user login.
- **Login.java**: User login logic.
- **ManageCategory.java**: Logic for managing product categories.
- **PlaceOrder.java**: Logic for placing new orders.
- **Signup.java**: User signup logic.
- **VerifyUser.java**: Logic for verifying users.
- **ViewBillsOrderPlacedDetails.java**: Logic for viewing bill and order details.
- **ViewEditDeleteProduct.java**: Logic for viewing, editing, and deleting products.

### Form Files

- **AddNewProduct.form**
- **ChangePassword.form**
- **ChangeSecurityQuestion.form**
- **ForgotPassword.form**
- **Home.form**
- **Login.form**
- **ManageCategory.form**
- **PlaceOrder.form**
- **Signup.form**
- **VerifyUser.form**
- **ViewBillsOrderPlacedDetails.form**
- **ViewEditDeleteProduct.form**

## Installation

To run the Cafe Management System on your local machine, follow these steps:

1. **Clone the Repository**: Clone the project repository to your local machine using the command:
   ```sh
   git clone https://github.com/yourusername/cafe-management-system.git
   ```

2. **Open in IDE**: Open the project in your preferred Java IDE (e.g., NetBeans, IntelliJ IDEA).

3. **Build the Project**: Build the project to ensure all dependencies are resolved.

4. **Run the Application**: Execute the `CafeManagementSystem.java` file to start the application.

## Usage

1. **Sign Up**: New users can sign up for an account.
2. **Log In**: Existing users can log in using their credentials.
3. **Place Orders**: Users can place new orders through the `PlaceOrder` interface.
4. **Manage Menu**: Admins can add, edit, or delete menu items through the `ManageCategory` and `ViewEditDeleteProduct` interfaces.
5. **View Bills**: Users can view their bills and order details through the `ViewBillsOrderPlacedDetails` interface.
6. **User Management**: Admins can verify users and manage security questions through the `VerifyUser` and `ChangeSecurityQuestion` interfaces.
