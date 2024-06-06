**ATM Simulation in Java**
This repository contains a simple ATM simulation program written in Java. The program allows users to perform basic banking operations such as checking account balance, depositing funds, and withdrawing money from both checking and saving accounts.

**Table of Contents**
1. Introduction
2. Features
3. Class Structure
3.1 ATM
3.2 Account
3.3 OptionMenu
4.Usage

1. **Introduction**
The ATM simulation program provides a console-based interface for users to interact with their bank accounts. It allows users to login with a customer number and PIN, and perform various banking operations once authenticated.

2. **Features**
Login System: Users can login using a customer number and PIN.
Account Types: Users can choose to access either their checking or saving account.
View Balance: Users can view the balance of their checking or saving account.
Deposit Funds: Users can deposit funds into their checking or saving account.
Withdraw Funds: Users can withdraw funds from their checking or saving account.

3. **Class Structure**

3.1 **ATM**

The ATM class is the main class that runs the program. It extends the OptionMenu class to access its methods.

public class ATM extends OptionMenu {
    public static void main(String[] args) {
        OptionMenu options = new OptionMenu();
        options.getLogin();
    }
}

3.2 **Account**
The Account class contains fields and methods related to customer account information and operations. It includes methods for setting and getting customer details, calculating deposits and withdrawals, and handling user inputs for transactions.

3.3 **OptionMenu**
The OptionMenu class extends the Account class and provides the user interface for interacting with the ATM. It includes methods for user login, selecting account type, and performing specific operations like viewing balance, depositing, and withdrawing funds.

4. **Usage**
Login: Enter your customer number and PIN to login.
Select Account Type: Choose whether to access your checking or saving account.
Perform Operations: You can view the balance, deposit funds, or withdraw money from the selected account.
Exit: Choose to exit the program.
