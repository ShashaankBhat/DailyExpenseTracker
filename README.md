# Daily Expense Tracker

The Daily Expense Tracker is a personal finance web application that helps users track, manage, and visualize their daily expenses. Designed with simplicity and usability in mind, the app allows individuals to take control of their spending habits and build awareness of where their money goes.

## Features

- Add and view daily expenses
- Categorize expenses (e.g., Food, Travel, Utilities)
- Filter and search by date or category
- View summary charts to analyze spending patterns
- Responsive and intuitive user interface

## Tech Stack

**Frontend:**
- HTML5
- CSS3
- JavaScript

**Backend:**
- Java (Servlets & JSP)
- Apache Tomcat Server

**Database:**
- MySQL

## Folder Structure

```
DailyExpenseTracker/
│
├── assets/                         # Image, icons, or other static assets
├── css/                            # External CSS files for styling
├── fonts/                          # Font files used in the UI
├── includes/                       # Common PHP includes (header, footer, DB config)
├── js/                             # JavaScript files (form validations, interactivity)
├── sass/                           # SASS files (if using SCSS-based styling)
├── tables/                         # Exportable or formatted report tables
│
├── add-expense.php                 # Page to add new expense
├── change-password.php             # Page to change user password
├── dashboard.php                   # User dashboard showing summary
├── expense-datewise-reports.php   # Reports filtered by date
├── expense-datewise-reports-detailed.php
├── expense-monthwise-reports.php  # Reports filtered by month
├── expense-monthwise-reports-detailed.php
├── expense-reports.php            # General expense report
├── expense-reports-detailed.php
├── expense-yearwise-reports.php   # Reports filtered by year
├── expense-yearwise-reports-detailed.php
├── forgot-password.php            # Forgot password page
├── index.php                      # ✅ LOGIN PAGE (your entry point)
├── logout.php                     # Logout handler
├── manage-expense.php             # View / Edit / Delete expenses
├── register.php                   # User registration page
├── reset-password.php             # Reset password after OTP
├── user-profile.php               # User profile management
│
├── .gitignore                     # Git ignore rules
├── LICENSE                        # Project license
├── README.md                      # Project README
└── SQL File                       # Database structure (.sql file for importing)

```

## How to Run the Project

1. Clone the repository:
   ```
   git clone https://github.com/ShashaankBhat/DailyExpenseTracker.git
   ```

2. Open the project in VS Code or your IDE.

3. Import the project into Apache Tomcat (via Eclipse or IntelliJ if needed).

4. Set up the MySQL database:
   - Create a new database: `expense_tracker`
   - Run the SQL script in `database/expense_tracker.sql` to create tables

5. Update DB credentials in the Java code if necessary.

6. Start the Tomcat server and navigate to:
   ```
   http://localhost:8080/DailyExpenseTracker/
   ```

## Author

**Shashank Bhat**  
Final-year Computer Science Engineering student  
GitHub: [ShashaankBhat](https://github.com/ShashaankBhat)


**Saniya Sheldarkar**  
Final-year Computer Science Engineering student  
GitHub: [ShashaankBhat](https://github.com/SaniyaSheldarkar)



## License

This project is licensed under the MIT License.
