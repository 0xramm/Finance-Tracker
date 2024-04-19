# Finance Tracker Flask App

This Flask-based web application serves as a comprehensive finance tracker, enabling users to manage their expenses and income securely. It provides features for user registration, authentication, transaction management, and analytical insights into spending habits.

## Features

- **User Authentication**: Secure registration and login functionality.
- **Transaction Management**: Add, delete, and view expense and income transactions.
- **Analytics**: Insights into spending patterns by payment method and category.
- **Responsive Interface**: User-friendly design for easy navigation and interaction.

## Live Preview
```
https://0xramm.pythonanywhere.com/
```

## Screenshots

<!-- Add screenshots of your application here -->
#### Login Page
![Login Page](screenshots/login.png)
#### Registration Page
![Registration Page](screenshots/registration.png)
#### Dashboard
![Dashboard](screenshots/dashboard.png)
#### Transaction_page
![Transaction_page](screenshots/transactions.png)
#### Add Transaction Popup
![Add Transaction Popup](screenshots/add_transaction.png)
#### Statistics page
![Statistics page](screenshots/statistics.png)




## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/0xramm/Finance-Tracker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Finance-Tracker
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Initialize the SQLite database:

   ```bash
   python app.py
   ```

2. Open the application in your web browser:

   ```
   http://localhost:5000/
   ```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your_feature_name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your_feature_name`).
6. Create a new pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/): Web framework for Python.
- [SQLite](https://www.sqlite.org/): Lightweight, serverless database engine.
- [Chart.js](https://www.chartjs.org/): JavaScript library for data visualization.
