
#  Digital Identity Hub
 Digital Identity Hub is a comprehensive web application designed to manage personal information across various departments and facilitate the creation of National Identity Cards (NIC). It offers a user-friendly interface for users to input and manage their data securely, with dedicated sections for marriage, education, insurance, medical history, travel, and NIC creation.

## Features

1. Departmental Management:

Organize Personal Information :                      

Users can categorize and manage their personal data into different departments, including marriage, education, insurance, medical history, and travel.

Each department provides dedicated forms for inputting and organizing specific types of information related to the respective category.

2. NIC Creation :

Generate National Identity Cards (NIC):

The application facilitates the creation of National Identity Cards for users based on the essential information collected through the application.

Users can request the generation of their NIC, which includes key details such as personal identification information and relevant data from various departments.

3. User Data Editing :

Easy Data Editing :

Users have the flexibility to edit their own data within each department after filling out the required forms.
Editable fields are provided, allowing users to update their information as needed to ensure accuracy and completeness.

4. Admin Panel:
Secure Access for Administrators   :

Administrators have secure access to an admin panel, which provides comprehensive visibility and control over all data across departments.

Authorized administrators can view, edit, and manage user data, ensuring compliance with organizational policies and regulatory requirements.

5. Access Data on Additional Page
View Filled Forms:

Users can conveniently access all the information they have filled out in the forms on an additional page dedicated to displaying their data.

This feature provides users with a centralized location to review and verify the accuracy of the information they have submitted across different departments.

6. Comprehensive Data Display:

The additional page presents the filled forms in a comprehensive and organized manner, allowing users to easily navigate through different sections such as marriage, education, insurance, medical history, travel, and more.

Users can view details of each submitted form, including dates, descriptions, and any uploaded documents or attachments.

7. Enhanced User Experience :
By offering access to their filled forms on a separate page, the application enhances the user experience by providing a seamless and intuitive way for users to interact with their data.
Users can quickly find and reference specific information without the need to navigate through individual form submissions.

8. Privacy and Security:

Strict privacy and security measures are implemented to ensure that users' data remains confidential and protected. Access to the additional page is restricted to authenticated users, and sensitive information is encrypted to prevent unauthorized access.

## Installation

To run Digital Identity Hub locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone <repository_url>
    ```

2. Navigate to the project directory:

    ```bash
    cd identity-hub
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm run dev
    ```
    This project is built using React Vite, a fast build tool for modern web development. React Vite provides a lightning-fast development experience by leveraging native ES Module (ESM) support in modern browsers. If you're unfamiliar with React Vite, you can learn more about it [here](https://vitejs.dev/).

## Usage/Examples

1. User Registration and Login:
Registration:

To register for an account, navigate to the registration page and fill out the required information.
Click the "Register" button to create your account.

Login:

If you already have an account, go to the login page and enter your credentials (username/email and password).
Click the "Login" button to access your account.

2. Data Input:
Inputting Data:

After logging in, navigate to the respective department (e.g., marriage, education) where you want to input your information.
Fill out the provided forms with the required details, such as personal information, dates, and descriptions.
Click the "Submit"  button to save your data.

3. User Data Editing:
Editing Data:
To edit your data, go to the department where the information is located.
Locate the entry you want to edit and click on the "Edit" button.
Modify the necessary fields and save your changes.

4. NIC Creation:
Requesting NIC Creation:
Once you have filled out all required information across departments, go to the NIC creation section.
Review the details displayed and confirm that they are accurate.
Click the "Request NIC" button to initiate the NIC creation process.

5. Admin Panel:
Accessing Admin Panel:
Only administrators have access to the admin panel. If you are an administrator, log in using your credentials.
Navigate to the admin panel section to view and manage all data across departments.

6. Data Management:
Managing Data:
Users can manage their data by accessing the respective department and making necessary updates or deletions.
Use the provided forms and controls to edit, delete, or add new information as needed.

7. Common Tasks:
Updating Information:
To update your contact information, educational qualifications, or other details, navigate to the relevant department and follow the steps for data editing.
Ensure that all changes are saved correctly.

8. NIC Generation:
Generating NIC:
After requesting NIC creation and confirming the details, wait for the system to process your request.
Once the NIC is generated, you will receive a notification or be able to download the NIC from your account dashboard.

9. Error Handling:
Handling Errors:
If you encounter any errors or issues during data input, NIC creation, or other processes, refer to the error messages displayed on the screen for guidance.
Check for any invalid inputs or missing information and correct them accordingly.


## file structure
|-- src

       |-- App.js
       |-- index.js
       |-- components
       |     |-- common
       |     |     |-- Header.js
       |     |     |-- Footer.js
       |     |
       |     |-- auth
       |     |     |-- Login.js
       |     |     |-- Register.js
       |     |
       |     |-- dashboard
       |     |     |-- Dashboard.js
       |     |
       |     |-- departments
       |           |-- education
       |           |     |-- EducationForm.js
       |           |
       |           |-- employment
       |           |     |-- EmploymentForm.js
       |           |
       |           |-- marriage
       |           |     |-- MarriageForm.js
       |           |
       |           |-- medical
       |                 |-- MedicalHistory.js
       |
       |-- pages
            |-- Home.js
            |-- About.js
            |-- Contact.js
            |-- NotFound.js

## Dependencies

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/)
- [Firebase](https://firebase.google.com/)

- **Firebase Authentication**: Used for user authentication and login functionality.

  - **Firebase Firestore**:
   Used as a database to store and manage application data.
  ## Firebase Usage

This project utilizes Firebase for authentication and data storage:

### Authentication

Firebase Authentication is used to handle user authentication and login functionality. Users can sign up, sign in, and sign out securely using Firebase Authentication.

### Data Storage

Firebase Firestore, a NoSQL cloud database, is used to store and manage application data. Data such as user profiles, form submissions, and other relevant information are stored securely in Firestore collections.

## Project Description

Identity Hub is a web application designed to streamline the management of personal information across various departments and facilitate secure access to user data. With a focus on simplicity and user-friendliness, Identity Hub offers the following features:

Departmental Management:
Organize personal information into different categories such as marriage, education, insurance, medical history, and travel. Users can conveniently update and manage their data within each department.

User Authentication:
Powered by Firebase Authentication, Identity Hub ensures secure user authentication and login functionality. Users can sign up, sign in, and securely access their data with peace of mind.

Data Storage and Security:
Utilizing Firebase Firestore, Identity Hub securely stores and manages user data. With robust security measures in place, users can trust that their personal information is protected and accessible only to authorized individuals.

Seamless User Experience:
Identity Hub offers a seamless user experience with intuitive navigation and responsive design. Whether accessing the application from a desktop or mobile device, users can easily interact with their data and perform necessary actions.
