# Banking-ATM-program-python-

Bank Account Manager

The goal is to create a class called Account which will be an abstract class for three other classes called CheckingAccount, SavingsAccount and BusinessAccount. Then you should manage credits and debits from these accounts through an ATM style program.
Project Scope

To tackle this project, first consider what has to happen.

    There will be three different types of bank account (Checking, Savings, Business)
    Each account will accept deposits and withdrawals, and will need to report balances

Project Wishlist

We might consider additional features, like:

    impose a monthly maintenance fee
    waive fees for minimum combined deposit balances
    each account may have additional properties unique to that account:
        Checking allows unlimited transactions, and may keep track of printed checks
        Savings limits the number of withdrawals per period, and may earn interest
        Business may impose transaction fees
    automatically transfer the "change" for debit card purchases from Checking to Savings,
    where "change" is the amount needed to raise a debit to the nearest whole dollar
    permit savings autodraft overdraft protection
