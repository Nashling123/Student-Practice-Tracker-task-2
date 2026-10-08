🎓 Student Management System

A modern and responsive Student Management System developed using React.js. This project provides a simple and user-friendly platform for managing student registration, login, student records, and practice sessions.

The application demonstrates important React concepts such as Components, Props, State Management, useState, useEffect, Conditional Rendering, Event Handling, and localStorage.

📌 Project Overview

The Student Management System is designed to provide a centralized platform for managing student information.

The system follows a simple workflow:

Register → Login → Dashboard → Manage Students → Practice Tracker

Students can register an account, log in to the system, add student information, view registered students in a table, search student records, delete records, and track their practice sessions.

The project also includes a Student Practice Tracker that demonstrates React state and lifecycle concepts.

🚀 Key Features
🔐 1. Registration
New users can create an account.
Registration details are stored using browser localStorage.
Basic form validation is provided.
Registered users can use their credentials to log in.
🔑 2. Login
Users can log in using their registered credentials.
Login status is maintained using application state.
Invalid login details are handled with an error message.
Users can securely log out from the application.
🎓 3. Student Management

The system allows users to manage student information.

Student details include:

Student Name
Register Number
Department
Email
Phone Number
Year

Users can:

Add new students
View student records
Search students
Delete student records
Display records in a structured table
📊 4. Dashboard

The dashboard provides a quick overview of the application.

It displays information such as:

Total Students
Practice Sessions
Student Details
Application Status

The dashboard provides a simple and attractive interface for accessing different features.

📝 5. Student Practice Tracker

The Student Practice Tracker is the main React practical feature of this project.

The tracker demonstrates:

React Props
React State
useState
useEffect
Component lifecycle
Conditional rendering
Event handling

The student profile displays:

Name: Anu
Department: CSE
Year: 3rd Year

➕ 6. Complete Practice

The Complete Practice button increases the practice count by 1.

For example:

Initial Count → 0

Complete Practice
        ↓
Count → 1

Complete Practice
        ↓
Count → 2

The count is managed using React's useState().

🔄 7. Reset Practice

The Reset button resets the practice count back to zero.

Example:

Practice Count → 5

Click Reset

Practice Count → 0
👁️ 8. Show / Hide Student Profile

The application includes a Show Profile / Hide Profile button.

When the profile is hidden:

The StudentProfile component is unmounted.
The Header remains visible.
The Footer remains visible.

When the profile is shown again:

The StudentProfile component is mounted again.
The practice tracker becomes visible.

This demonstrates conditional rendering and component mounting/unmounting.

⚛️ React Concepts Used
1. Components

The application is divided into reusable React components.

Examples:

App
Header
StudentProfile
StudentTable
Login
Register
Dashboard
Footer

This makes the application easier to manage and maintain.

2. Props

Student information is passed from the App component to the StudentProfile component using props.

Example:

Name → Anu
Department → CSE
Year → 3rd Year

Props are used to pass data between React components.

3. useState

The application uses useState() to manage dynamic data.

The practice count starts with:

const [count, setCount] = useState(0);

The count is updated using:

setCount(count + 1);

and reset using:

setCount(0);
4. useEffect

The useEffect() hook is used to update the browser document title whenever the practice count changes.

Example:

Practice Sessions: 0
Practice Sessions: 1
Practice Sessions: 2

The effect runs whenever the count changes.

5. Lifecycle and Cleanup

The StudentProfile component also demonstrates cleanup.

When the component is removed, the previous browser title is restored.

This demonstrates the lifecycle behavior of a React component.

💾 Local Storage

The application uses browser localStorage to store information.

It can be used for:

Registered user information
Login-related data
Student records

This allows information to remain available even after refreshing the browser.

🛠️ Technologies Used
Frontend
React.js
JavaScript
HTML5
CSS3
React Concepts
Components
Props
State
useState
useEffect
Conditional Rendering
Event Handling
Component Lifecycle
Browser Technology
Local Storage
DOM
Browser Document Title
📁 Project Structure
student-management-system/
│
├── index.html
│
├── README.md
│
└── assets/
    └── images/

If the project is separated into React files, the structure can be:

student-management-system/
│
├── src/
│   ├── App.jsx
│   ├── StudentProfile.jsx
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── Login.jsx
│   ├── Register.jsx
│   └── StudentTable.jsx
│
├── public/
│
├── package.json
└── README.md
🎯 Student Practice Tracker Testing

The following test cases can be used to verify the project.

Test Case 1 – Initial State
Practice Count = 0
Test Case 2 – Complete Practice Once

Click:

Complete Practice

Expected result:

Practice Count = 1
Test Case 3 – Complete Practice Twice

Click the button two times.

Expected result:

Practice Count = 2
Test Case 4 – Reset

Click:

Reset

Expected result:

Practice Count = 0
Test Case 5 – Hide Profile

Click:

Hide Profile

Expected result:

Student profile disappears.
Header and Footer remain visible.
Test Case 6 – Show Profile

Click:

Show Profile

Expected result:

Student profile appears again.
Test Case 7 – Browser Title

The browser title changes according to the practice count.

Example:

Practice Sessions: 0
Practice Sessions: 1
Practice Sessions: 2
🎨 User Interface

The application provides a clean and responsive interface with:

Modern dashboard
Navigation header
Student cards
Student table
Practice tracker
Login page
Registration page
Responsive buttons
Footer section

The interface is designed to be simple and easy to use.

📱 Responsive Design

The application is designed to work on different screen sizes.

It can be accessed from:

Desktop
Laptop
Tablet
Mobile devices
🔒 Data Management

Student and registration information can be stored in browser local storage.

This provides a simple client-side data management solution without requiring a separate database for this practical implementation.

▶️ How to Run the Project
Method 1 – Using Browser

If using the single-file version:

Download or clone the repository.
Open the project folder.
Open index.html.
The application will run in the browser.
Method 2 – Using VS Code
Open VS Code.
Open the project folder.
Open index.html.
Use Live Server if available.
Open the generated browser page.
💻 GitHub Repository

Repository:

https://github.com/Nashling123/student-management-system

📌 Demo Credentials

No fixed credentials are required if registration is enabled.

Testing

First register a user:

Name: Anu
Email: anu@example.com
Password: 123456

Then use the registered credentials to log in.

🧪 Practical Verification

The project successfully demonstrates the required React functionality:

✓ Header created
✓ Footer created
✓ Student information passed using Props
✓ Practice count managed using useState
✓ Complete Practice button implemented
✓ Reset button implemented
✓ useEffect implemented
✓ Browser title updated
✓ Cleanup function implemented
✓ Show/Hide Profile implemented
✓ Component mount/unmount demonstrated
✓ Student records displayed in table
✓ Registration implemented
✓ Login implemented
✓ Data stored using localStorage
🎓 Learning Outcomes

Through this project, the following concepts were practiced:

Understanding React components.
Passing data using props.
Managing application state using useState.
Handling user events.
Using useEffect for side effects.
Understanding component lifecycle.
Implementing cleanup functions.
Using conditional rendering.
Working with browser localStorage.
Creating reusable and responsive UI components.
Managing student records.
Building a complete React-based web application.
🔮 Future Enhancements

The project can be extended with additional features such as:

MongoDB database integration
Node.js and Express backend
Admin dashboard
Student authentication
Password encryption
Student profile editing
Attendance management
Assignment tracking
Practice history
Progress charts
Course management
Notifications
Search and advanced filtering
Cloud deployment
👩‍💻 Developer

Nashling Fathima T.

B.E. Computer Science and Engineering
Kumaraguru College of Technology
2024–2028

📄 Project Type

Academic / React Practical Project

Project Title

Student Practice Tracker

Main Technologies

React.js | JavaScript | HTML | CSS | LocalStorage

⭐ Conclusion

The Student Management System provides a simple platform for managing student information and tracking student practice sessions.

The project demonstrates important React concepts including Props, State, useState, useEffect, Conditional Rendering, Component Lifecycle, and Event Handling.

The Student Practice Tracker specifically demonstrates how React state changes can dynamically update the user interface and browser document title while also showing component mounting and unmounting behavior.

This project provides a strong foundation for developing larger student management and academic tracking applications in the future.
