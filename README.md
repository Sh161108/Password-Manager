# Password Manager Project

This is a simple password manager project implemented in JavaScript. It allows users to add, view, search, edit, and delete passwords for various websites. Access to the system is protected by a master password.

## Features

- Master password protection
- Add new credentials (username, password, site)
- View saved credentials
- Search for credentials by username or site
- Edit existing credentials
- Delete credentials

## How to Use

1. **Master Password Check**: 
   - When the script runs, it prompts the user to enter the master password. The default master password is `pass@43`.
   - The user has three attempts to enter the correct master password. If the correct password is entered, access is granted. Otherwise, the user is locked out.

2. **Adding Passwords**:
   - After gaining access, the user can add new credentials by providing a username, password, and site name.
   - The user is prompted to add more passwords if needed.

3. **Viewing Passwords**:
   - The user can choose to view all saved credentials.
   - Each credential is displayed with its username, password, and site name.

4. **Searching Passwords**:
   - The user can search for credentials by entering a username or site name.
   - Matching credentials are displayed with their details.

5. **Editing Passwords**:
   - The user can edit an existing credential by providing the username and site name of the credential.
   - The user can then enter a new password for the credential.

6. **Deleting Passwords**:
   - The user can delete credentials by providing the username, password, and site name of the credential to be deleted.
   - If a matching credential is found, it is deleted from the saved credentials.

## Local Storage

- Credentials are stored in the browser's local storage, allowing data to persist across sessions.

## Setup

1. Clone this repository.
2. Open `index.html` in a web browser to run the password manager.

## Note

- This project is for educational purposes. Storing passwords in local storage is not secure for real-world applications. Use a professional password manager for sensitive information.

## License

This project is open source and available under the [MIT License](LICENSE).
