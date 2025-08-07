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
├── src/
│   ├── controller/
│   ├── model/
│   └── view/
├── WebContent/
│   ├── jsp/
│   ├── css/
│   ├── js/
│   └── index.jsp
├── database/
│   └── expense_tracker.sql
└── README.md
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

## License

This project is licensed under the MIT License.