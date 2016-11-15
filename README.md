Get the username and account balance of the 3 users with the lowest balances, sort lowest to highest balance.

Get all users with account balances that are more than $100. Add a new record. The bank is losing money in Miami and Phoenix and needs to unload low transaction customers: Delete users that reside in miami OR phoenix and have completed fewer than 5 transactions.

SELECT * FROM syntax_practice WHERE CITY = 'chicago';

SELECT * FROM syntax_practice WHERE USERNAME LIKE '%a%';

UPDATE syntax_practice SET ACCOUNT_BALANCE = 10.00 WHERE account_balance = 0 AND transactions_attempted = 0;

SELECT * FROM syntax_practice WHERE transactions_attempted > 9;

SELECT * FROM syntax_practice WHERE account_balance > 0 ORDER BY ACCOUNT_BALANCE DESC LIMIT 3;

SELECT username, account_balance FROM syntax_practice WHERE account_balance > 0 ORDER BY ACCOUNT_BALANCE ASC LIMIT 3;
