# REST-API-MONGODB
Spring Boot Rest API with MongoDB 

API Path:
{url}/expense

Examples:

Add Expense Restaurant:

Post:

{
    "expenseName": "Restaurant Good Fork",
    "expenseCategory": "RESTAURANT",
    "expenseAmount": 50
}

Add Expense Movie:

Post:

{
    "expenseName": "Movies",
    "expenseCategory": "ENTERTAINMENT",
    "expenseAmount": 30
}

Update Expense:

Put
 {
        "id": {Id in database},
        "expenseName": "Movies",
        "expenseCategory": "ENTERTAINMENT",
        "expenseAmount": 150
}

Get Expenses by Name
{url}/expense/{expenseName}

Delete Expense
{url}/expense/{Id in database}
