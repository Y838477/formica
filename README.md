# Formica

This application allows people to monitor the monthly budget like the ant in famous french "fables de la Fontaine".

## Registering payments and incomes

Daily and monthly payments are registered in a journal

In other words, journal entry contains a list of payments and incomes.

### Journal entry

A journal entry has:

* a list of financial transactions
* a balance

### Payment

A payment has few attributes:

* date of payment
* supplier
* description
* mean of payment
* amount
* VAT amount

### Income

An income has also few attributes:

* date of payment
* source (salary, rent, shares, etc...)
* description
* mean of payment
* amount
* income tax percentage

### Dashboard

All of these transactions can be monitored and analysed through the main dashboard:

This dashboard allows the user to operate CRUD operation on financial transactions and get a clear picture of the main key metrics.

* Monthly fixed expenses
* Monthly fixed income
* Estimated amount that can be saved monthly
* etc...