# Project Title: Admin Panel with User Management and Data Operations

## Description:

This Java-based Object-Oriented Programming (OOP) project is an Admin Panel that provides user authentication, account creation, and data management functionalities. The project includes features such as signing up, logging in, adding, updating, and deleting user data.

## Features:

1. **User Authentication:**
   - The admin panel includes a sign-in button that requires a valid username and password for access.
   - If incorrect credentials are entered, an error message is displayed.

2. **Account Creation:**
   - Users can sign up for an account by providing a unique username and a password.
   - Password and confirm password fields are validated, and if they do not match, an error message is shown.
   - Successful account creation stores user data in an `input.txt` file.

3. **Login Window:**
   - Upon successful signup, users are redirected to a `login.java` window.
   - The login window has three text fields for entering first name, email, and a phone number.

4. **Data Operations:**
   - The login window includes three buttons: "Add Data," "Delete," and "Update."
   - "Add Data" button stores the entered information in an `info.txt` file.
   - "Update" button allows users to modify their data.

## Usage:

1. **Sign Up:**
   - Click the "Sign Up" button on the admin panel.
   - Enter a unique username, set a password, and confirm the password.
    <img width="949" alt="Screenshot 2024-02-04 214324" src="https://github.com/sadique21hs/OOP-Project/assets/152019380/e1d92bfc-a9e2-46f8-9e06-7f580d6f1650">
    
   - If successful, the account is created, and user data is stored in `input.txt`.
     
     <img width="273" alt="Screenshot 2024-02-04 214352" src="https://github.com/sadique21hs/OOP-Project/assets/152019380/478e0b17-84b0-474d-9352-dffe2710c242">

2. **Login:**
   - After signing up, click the "Login" button and enter your username and password.

3. **Add Data:**
   - Upon successful login, fill in the first name, email, and phone number text fields.
   - Click the "Add Data" button to store the entered information in `info.txt`.

4. **Update:**
   - Use the "Update" button to modify the existing data.

5. **Delete:**
   - Implement the "Delete" button to remove user data.

## File Structure:

- `AdminPanel.java`: Main class for the admin panel GUI.
- `SignUp.java`: Manages user sign-up functionality.
- `Login.java`: Handles user login and data entry.
- `DataOperations.java`: Class for managing data operations (Add, Update, Delete).
- `input.txt`: File to store user account information.
- `info.txt`: File to store user data entered through the login window.

## Dependencies:

- This project is written in Java and may require Java SE Development Kit (JDK) for compilation and execution.

## Instructions:

1. Clone the repository.
2. Compile and run the `AdminPanel.java` file.
3. Follow the on-screen instructions to sign up, log in, and perform data operations.

Feel free to explore and enhance this project. If you encounter any issues or have suggestions for improvement, please open an issue on GitHub.

Happy coding!
