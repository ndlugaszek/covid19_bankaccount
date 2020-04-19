# covid19_bankaccount
The application, which creates a bank account.  

You can create 3 types of the bank account:
1) the account for the Polish citizens
2) the account for the Polish company
3) the account for the Foreigners

After creation, you can make some operations:
1) deposit
2) withdraw - with 1000 daily limit, for foreigners without limit
3) close - due to government loan, the companies cannot close the account

The application write all customers to the CSV file, then reads from the CSV file.
