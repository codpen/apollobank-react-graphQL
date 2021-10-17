# apollobank 🚀

A fullstack GraphQL banking application built using React, Node & TypeScript.

## Functions

- Login/register
- Dashboard
- Accounts
- Transactions
- Credit cards
- Settings
- Spending for this month chart
- Dummy data generator using faker

![dashboard](images/dashboard.png)

## Specifications

### Server side

- Apollo Server
- bcryptjs
- cors
- Express
- GraphQL
- faker
- jsonwebtoken
- TypeGraphQL
- TypeORM
- TypeScript
- PostgreSQL

### Client side

- Apollo React Hooks
- FontAwesome Icons
- Material UI
- Recharts
- Formik
- Yup

## Todo

- [ ] Don't allow the user to destroy an account if they are in debt or their account balance > 0
- [ ] When deleting and destroying an account, alert the user with another dialog to check if they would like to proceed with this action.
- [ ] Update the chart on the dashboard to show spending such that the y axis is the users account balance.
- [ ] Sort transactions by date & sort chart data by date.
- [ ] Fetch exchange rates from an API.
