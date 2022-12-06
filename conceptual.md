### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  - PostgreSQL is a RDBMS (Relational Database Management System) that is commonly used. It stores data and follows SQL standards

- What is the difference between SQL and PostgreSQL?
  - PostgreSQL data management system. SQL is the language that is used to communicate through PostgreSQL or other databases.

- In `psql`, how do you connect to a database?
  - \c DATABASE_NAME

- What is the difference between `HAVING` and `WHERE`?
  - WHERE is applied to the individual rows, HAVING is applied to groups of those rows. 

- What is the difference between an `INNER` and `OUTER` join?
  - INNER joins returns the results that have matching values in both the tables youre joining, OUTER joins returns everything in both tables you join. 

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  - LEFT OUTER join returns all results from the left table and matched records form the right table, RIGHT OUTER join does the opposite -  returns all results from the right table and the matching records for the left table. 

- What is an ORM? What do they do?
  - ORM (object relational mapping) is a way to communicate data in a relational database and programming language like python. A common ORM is SQLAlchemy. It is a great tool to keep our data model in one place/langague and is neat. 

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  - AJAX is a client side request which can be easily done using the AJAX library, and dont need to invovle Flask in the API. Server side requests are easier for the server to store/process data and can be protected with password/key which would be hidden from Javascript (client side)

- What is CSRF? What is the purpose of the CSRF token?
  - CSRF stands for Cross-Site Request Forgery which allows forms from any site to submit to any other sites and cause major security issues. CSRF Token is used to protect that, the token is included in the HTML form and is checked by the server when the form submits.

- What is the purpose of `form.hidden_tag()`?
  - form.hidden_tag() is the syntax we need to include in our HTML to generate the hidden field that is used as a token for our CSRF security. 
