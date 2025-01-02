# Daily Expense Tracker 
Welcome to the **Daily Expense Tracker** project! This web application allows users to efficiently track their daily expenses and generate detailed reports based on date ranges.
## Features

- **User Authentication**: Secure login and session management to ensure only authorized users can access their expense data.
- **Expense Reporting**: Generate detailed, date-wise expense reports that sum up daily expenses for a specified period.
- **Responsive Design**: User-friendly interface that works seamlessly across different devices and screen sizes
## Technologies Used

- **Backend**: PHP and MySQL
- **Frontend**: HTML, CSS (Bootstrap), and JavaScript
- **Libraries**: jQuery, Font Awesome, Datepicker
- ### Prerequisites

- A web server (e.g., Apache)
- PHP 7.x or higher
- MySQL
- Composer (for managing dependencies)

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Joseph551da/daily-expense-tracker/
    ```
2. **Navigate to the project directory**:
    ```bash
    cd daily-expense-tracker
    ```
3. **Install Dependencies**:
    ```bash
    composer install
    ```
4. **Configure the Database**:
    - Create a MySQL database.
    - Import the database schema from the `db` directory.
    - Update the database connection settings in `includes/dbconnection.php`.

5. **Start the Server**:
    - If using Apache, ensure the `daily-expense-tracker` folder is within your `htdocs` directory.
    - Start your Apache server.
  
 ## Contributing

We welcome contributions to improve the Daily Expense Tracker. Here's how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add a feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a Pull Request.

 ## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by various expense tracking applications.
- Thanks to the open-source community for their valuable resources.

  ---

Thank you for using the **Daily Expense Tracker**! If you have any questions or feedback, feel free to open an issue in the repository.
