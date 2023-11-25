# Sign-up-Form
![image](https://github.com/wambexper/Sign-up-Form/assets/118281574/19ca9ae5-e474-4684-93ad-80a311bc2de8)
This project implements a User Authentication system utilizing local storage. It comprises two main pages: "Signup" and "Profile."

Features
Signup Page:

Mandatory fields for user details input.
Successful storage of user data in local storage, including a randomly generated 16-byte access token.
Profile Page:

Display of user details from local storage.
Implementation of a "Logout" button that clears local storage and redirects to the signup page.
Access Control:

Preventing manual navigation to "Profile" without an access token.
Redirection from "Signup" to "Profile" for logged-in users.
Success and Error Messages:

Display of appropriate messages for success and error scenarios.
Uses
The User Authentication System using Local Storage serves the following purposes:

Secure User Signup: Allows users to securely sign up by providing necessary details while ensuring their information is stored safely in the browser's local storage.

Profile Display: Displays user details on the profile page retrieved from local storage after successful signup, offering users a personalized experience.

Logout Functionality: Provides a convenient logout mechanism, clearing user data from local storage and ensuring secure logout functionality.

Access Control: Implements access control measures to prevent unauthorized access to certain pages, ensuring a secure and controlled user experience.

Success and Error Messaging: Offers clear and concise feedback to users through success and error messages, enhancing user understanding and interaction with the system.

This system aims to provide a seamless and secure user authe
