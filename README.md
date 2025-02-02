# User-interface-specification-document
Prepared a user interface specification document for P.I. Works' assingment.
# User Management Screen - UI Specification Document

## 1. Overview
This document provides a detailed specification of the **User Management Screen** in the system. It includes the functionalities, UI components, and behaviors that developers should implement.

## 2. Page Components and Layout
### 2.1. User List Table
- Displays a list of existing users with the following columns:
  - **ID**: Unique identifier for each user.
  - **User Name**: The username of the user.
  - **Email**: User's email address.
  - **Enabled**: Boolean flag indicating if the user is active (`true`) or disabled (`false`).

### 2.2. New User Form (Right Panel)
- **Username** (Text Input) – Required
- **Display Name** (Text Input) – Optional
- **Phone** (Text Input) – Optional
- **Email** (Text Input) – Required
- **User Roles** (Dropdown) – Options: `Guest`, `Admin`, `SuperAdmin`
- **Enabled** (Checkbox) – Whether the user is active or not

## 3. Actions and Behaviors
| **Action** | **Behavior** |
|------------|-------------|
| **Click "New User"** | New User Form displays. |
| **Click on Save User** | Saves newly created user and goes back to the User List component. |
| **Hide Disabled User** | Removes disabled users in the User List. |
