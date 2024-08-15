JJ-ATM Project

1. Introduction
The project simulates my ATM machine, branded as "JJ-ATM." It allows users to perform basic banking operations like PIN generation, PIN change, balance inquiry, withdrawal, and deposit.
The project began with a plan to create an interactive ATM simulation that would mimic real-life ATM operations.
The class Atm initializes with a default PIN ("1234") and a large balance ($1,000,000,000).
The __menu method is automatically invoked, presenting the user with a list of options.

3. Menu Interaction
The user can choose to generate a PIN, change their PIN, check their balance, withdraw money, deposit money, or exit the program.
Depending on the user's input, the corresponding method is called to handle the requested operation.
PIN Management: The user can set a new PIN, provided the default PIN is still active. If the PIN is already set, the user is advised to change it instead.
The user can change the existing PIN after verifying the current PIN.

4. Transactions
Check Balance: The balance is displayed after verifying the PIN.
Withdraw: The user can withdraw money in multiples of 100, provided they have sufficient funds.
Deposit: The user can deposit money in multiples of 100, which is then added to their balance.

5. Challenges Faced
Ensuring that user inputs are correctly validated, like PIN length, numeric checks was crucial to avoid errors.
Initial issues included incorrect PIN comparisons and improper menu navigation, which were resolved by adding debugging print statements and refining the logic.
