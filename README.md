# Expense Management Software
```
Coded By: sai lokesh
```
In these times of digitalization, all major organizations are aiming to automate most of their processes for better convenience. One important task for an organization involves the filing of expenses by employees for claiming reimbursements. These expenses also need to be approved / rejected by the appropriate authority.

A web application based on **react-redux** at the frontend and **Java** and **PostgreSQL** at the backend has been built to provide an automated solution to record and report business expenses.

This repository includes all the codes which the [Expense Management System](https://expense-management-system-rs.herokuapp.com/) website uses.

**UPDATE (28 Nov 2022)**: 

The link is not accessible anymore as Heroku, where the project was hosted, has stopped its Free Product plans. I might find an alternative sometime in the future and would update the README accordingly.

## Features
<ul type="square">
  <li> Login for employees (authentication with JWT Auth Token).
  <li> Add new employees when logged in as an <i>Administrator</i>.
  <li> Add new clients and projects.
  <li> Add new expenses with attachments.
  <li> View project and expense summaries.
  <li> Approval tab for approving / rejecting expense claims.
  <li> Feature to change password when the user wants.
  <li> The first time an employee logs in, they will have to set a strong password to access other features of the software. It is assumed that the <i>Administrator</i> is responsible for creating an initial password for a new employee to log in.
  <li> Protected routing - allows all pages, except the Login page, to be accessed only after a user has logged in. 
</ul>

