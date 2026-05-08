# Expense Tracker

A simple and intuitive expense tracking application built with React. Keep track of your daily expenses with ease.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 📋 Features

- **Add Expenses**: Add expenses with a title and amount
- **Delete Expenses**: Remove individual expenses from the list
- **Persistent Storage**: Expenses are saved to localStorage and persist across browser sessions
- **Real-time Updates**: Total expenses update automatically as you add or remove items
- **Responsive Design**: Clean and mobile-friendly interface

## 🚀 Demo link
https://expense-tracker-six-plum.vercel.app/

Track your expenses by entering:
- **Title**: Description of the expense (e.g., "Groceries", "Rent", "Coffee")
- **Amount**: Cost of the expense in your local currency

The app will automatically calculate and display your total expenses.

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mamykhoulalene-star/expense-tracker.git
Navigate to the project directory

bash
cd expense-tracker
Install dependencies

bash
npm install
Start the development server

bash
npm start
Open your browser

Visit http://localhost:3000 to view the app

📦 Project Structure
text
expense-tracker/
├── public/
│   └── index.html
├── src/
│   ├── App.js          # Main application component
│   ├── App.css         # Application styles
│   └── index.js        # Application entry point
├── package.json
└── README.md
💻 Usage
Enter the expense title in the text input field

Enter the expense amount in the number input field

Click the "Add Expense" button to add the expense to your list

View all expenses in the list below

Click the "Delete" button next to any expense to remove it

Monitor your total expenses at the bottom of the page

🎨 Styling
The application features a clean and modern design with:

Centered layout with maximum width of 500px

Green "Add Expense" button for adding items

Red "Delete" button for removing items

Clean typography and spacing

Responsive design that works on all screen sizes

🔧 Technical Details
Built With
React - Frontend library

React Hooks - State management (useState, useEffect)

localStorage - Client-side data persistence

CSS3 - Custom styling

Key Implementation Details
Uses useState hook for managing expenses, title, and amount state

Implements useEffect hook to sync state with localStorage

Input validation ensures non-empty titles and positive amounts

Unique IDs generated using Date.now() for each expense

🤝 Contributing
Contributions are welcome! Feel free to:

Fork the repository

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 Future Enhancements
Edit expense functionality

Expense categories

Date tracking for each expense

Export expenses to CSV

Charts and visualizations

Budget tracking and alerts

Dark mode support

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

👤 Author
Samy Khoulalene

GitHub: @mamykhoulalene-star

