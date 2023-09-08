**Password Manager Project**

**Overview:**
For this project, you and your partner will develop a Password Manager application. This application will allow users to securely store and manage their login credentials for various accounts. Below are the detailed requirements, concepts to include, and bonus features for this project.

**Requirements:**

1. **Log In System**:
   - Users must log in to run the program.
   - Provide a hint and limit the number of login attempts before the program shuts down.
   - First-time users can create a profile with the following requirements:
     - Username
     - Password (with specific requirements - see item 8)
     - First and last name
   - After registration, require users to log in.

2. **Account Storage**:
   - Create a method to take user input to store accounts (username and password) based on categories.
   - Accounts must be retrievable based on categories.
   - Each account must include:
     - Account name
     - Username
     - Password
     - Category

3. **Data Persistence**:
   - Save account information to a text file.

4. **Category Navigation**:
   - Allow users to navigate through the categories they have created.
   - Provide a list of categories for selection (e.g., home, work, entertainment, bills, etc.).

5. **Password Generator**:
   - Implement a password generator option.
   - Bonus: Include this as a class.
   - Half Bonus: Include this in a method.

6. **Account Management**:
   - Enable users to delete or modify passwords.

7. **Output Format**:
   - The program should provide output in a simple-to-understand format:
     ```
     Account: {accountName}
     Username: {username}
     Password: {password}
     ```

8. **Password Requirements**:
   - Passwords and user input must meet the following criteria:
     - Contains at least 1 capital character
     - Contains at least 1 number
     - Contains at least 1 special character (only certain special characters allowed)
     - At least 8 characters long
   - Bonus: Create a class to check for password requirements.
   - Half Bonus: Create a method to check for password requirements.

9. **Bonus Features**:
   - 10% Bonus: Save the file as a password-protected or encrypted file.
   - 5% Bonus: Create a method that calculates how long it would take to brute force break a password.
   - 15% Bonus: Save the information on a database.

**Computer Science Concepts to Include:**

1. User Input
2. Arrays, Lists, and ArrayLists
3. Utilizing built-in functions to create passwords
4. Loops
5. Multiple Classes (e.g., PasswordRecord, Library, OpenCloseFile)
6. Commenting in code
7. Handling exceptions gracefully to avoid runtime errors
8. User-friendly interface and smooth usability

**Project Management:**

- Create a design overview approved by your instructor before starting the project. Include features, implementation details, and assign responsibilities.
- Document any outside sources used, and provide commentary on their use.

**Example:**

If you need an example of a password manager, install the following program and explore its functionality:
[https://sourceforge.net/projects/keepass/files/KeePass%202.x/2.52/KeePass-2.52-Setup.exe/download](https://sourceforge.net/projects/keepass/files/KeePass%202.x/2.52/KeePass-2.52-Setup.exe/download)

**Note:**
This project challenges you to build a password manager with specific features and security measures. Ensure that your program is well-documented, user-friendly, and meets the specified requirements.
