## payees

List the unique payee/payer names that appear in transactions.

_FLAGS

This command lists unique payee/payer names which have been 
declared with payee directives (--declared), 
used in transaction descriptions (--used), 
or both (the default).

The payee/payer is the part of the transaction description before a | character 
(or if there is no |, the whole description).

You can add query arguments to select a subset of transactions. This implies --used.


Example:
```shell
$ hledger payees
Store Name
Gas Station
Person A
```
