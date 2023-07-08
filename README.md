# SQL Banking Operation with Python

This project is a simple banking system implemented using Python and SQL. It provides basic functionalities like creating a new account, depositing money, withdrawing money, transferring money between accounts, and checking the account balance.

## Requirements

To run this project, you need to have the following installed:

- Python 3
- MySQL Server

## Setup

1. Clone this repository to your local machine using the following command:

git clone https://github.com/Sauhardrajput/SQLBanking_operation_with_python.git

2. Install the required dependencies by running the following command:

pip install -r requirements.txt

3. Import the `banking.sql` file into your MySQL server to create the necessary database and tables. You can use any MySQL client or command-line tool to import the file.

4. Update the database connection details in the `banking.py` file. Modify the `db_config` dictionary with your MySQL server details:

python
db_config = {
    'host': 'localhost',
    'database': 'banking',
    'user': 'root',
    'password': 'your_password'
}
5. Run the `banking.py` file using the following command:

python banking.py

## Usage

Once you have set up the project, you can use the following commands to interact with the banking system:

- To create a new account:

create_account

- To deposit money into an account:

deposit <account_number> <amount>

- To withdraw money from an account:

withdraw <account_number> <amount>

- To transfer money between accounts:

transfer <from_account_number> <to_account_number> <amount>

- To check the balance of an account:

balance <account_number>

- To exit the banking system:

exit

## Contributing

If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request. Your contributions are always welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions regarding this project, please feel free to reach out to me:

- Name: Sauhard Rajput
- Email: sauhardrajput1@gmail.com
- GitHub: [Sauhardrajput](https://github.com/Sauhardrajput)
