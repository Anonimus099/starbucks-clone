Starbucks Coffee Company | Clone

This web application is a clone of the Starbucks website featuring a fully functional user registration and login system.

🚀 Features
Registration System

✅ Register new users
✅ Validate all form fields
✅ Password strength validation
✅ Email uniqueness check
✅ Automatic login after registration

Login System

✅ Login with email and password
✅ Check if the user exists
✅ Maintain login session
✅ Prevent repeated login attempts

Profile Management

✅ Display user information
✅ Profile page with detailed info
✅ Logout functionality
✅ Responsive design

Admin Panel

✅ View all registered users
✅ Option to clear all user data
✅ Display registration time

📁 Project Structure
starbucks/
├── index.html          # Home page
├── signin.html         # Login page
├── join.html           # Registration page
├── profile.html        # User profile page
├── admin.html          # Admin panel
├── starbucks.js        # Main JavaScript file
├── signin.js           # Login logic
├── join.js             # Registration logic
├── style/
│   ├── starbucks.css   # Main styles
│   ├── signin.css      # Login/registration styles
│   └── join.css        # Additional registration styles
└── img/                # Images and icons

🛠️ Technologies Used

HTML5 – Page structure
CSS3 – Styling and responsive design
JavaScript (ES6+) – Interactivity and logic
LocalStorage – User data storage
Responsive Design – Mobile-friendly layout

📋 Password Requirements

When registering, a password must include:
At least 8 characters
At least one uppercase letter
At least one lowercase letter
At least one number
At least one special character (!@#$%^&*(),.?":{}|<>)

🔐 Security

Input validation on all fields
Email uniqueness verification
Empty field prevention
Email format checking
Login time tracking

🎨 Design Highlights

Modern and clean interface
Fully responsive layout
Smooth animations and transitions
Starbucks-inspired color scheme
Intuitive navigation

🚀 How to Run the Project

Download all project files
Open index.html in your browser
To test the admin panel, open admin.html

📱 Supported Browsers

Chrome (recommended)
Firefox
Safari
Edge

🔧 Usage Instructions
Adding New Users

Go to the registration page (join.html)
Fill in all required fields
Click "Create account"
Logging In
Go to the login page (signin.html)
Enter your email and password
Click "Sign in"
Viewing Profile
Log in to your account
Click your name in the site header
Or go directly to profile.html
Admin Panel
Open admin.html
View all registered users
Use "Clear all users" to reset the data

📊 Data Storage

All user data is stored locally in your browser’s LocalStorage:
starbucksUsers – Array of all registered users
currentUser – Currently logged-in user information

🔄 Updates
Version 1.0

✅ Basic registration and login system
✅ Form validation
✅ Admin panel
✅ Profile page
✅ Responsive design

📞 Support

If you encounter issues or have questions:
Check the browser console for errors
Make sure all files are loaded correctly
Verify that LocalStorage is supported in your browser

📄 License

This project was created for educational purposes and is a clone of the official Starbucks website.
