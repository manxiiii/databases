### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  PostgreSQL is an open-source, object-relational database management system (DBMS)
- What is the difference between SQL and PostgreSQL?
  SQL is a standardized language used for interacting with relational databases, while PostgreSQL is a specific database management system that supports the SQL language and offers additional features and capabilities beyond the standard SQL specification. PostgreSQL is one of many implementations of SQL, and other DBMSs, like Oracle, MySQL, or SQL Server, also support the SQL language but may have different features and extensions specific to their platforms.
- In `psql`, how do you connect to a database?
  psql -U <username> -d <database_name> -h <host> -p <port>
- What is the difference between `HAVING` and `WHERE`?
  The main difference between WHERE and HAVING is the stage at which they are applied in the query execution process. The WHERE clause filters rows before grouping and aggregation, while the HAVING clause filters the grouped and aggregated data based on conditions. Consequently, HAVING can include conditions that involve aggregate functions like SUM, COUNT, or AVG.
- What is the difference between an `INNER` and `OUTER` join?
  It's worth noting that INNER JOIN is the most commonly used join type to retrieve matching records, while OUTER JOIN variants are used when you want to include unmatched rows as well. The specific join type you choose depends on the desired result and the relationship between the tables you are working with.
- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  It's important to note that although LEFT OUTER JOIN and RIGHT OUTER JOIN have different positioning and include unmatched rows from different tables, they are functionally equivalent. You can express a RIGHT OUTER JOIN as a LEFT OUTER JOIN by reversing the positions of the tables and the join condition, and vice versa.
- What is an ORM? What do they do?
  ORM stands for Object-Relational Mapping. It refers to a programming technique and a software tool that allows developers to interact with relational databases using object-oriented programming concepts. An ORM acts as a bridge between the object-oriented programming language and the relational database, providing a convenient and intuitive way to work with persistent data.
- What are some differences between making HTTP requests using AJAX
  and from the server side using a library like `requests`?
   AJAX requests are suitable for client-side interactivity, while server-side requests are useful for server-side processing, data retrieval, or server-to-server communication.
- What is CSRF? What is the purpose of the CSRF token?
  CSRF (Cross-Site Request Forgery) is a type of security vulnerability that occurs when an attacker tricks a victim into unintentionally executing unwanted actions on a web application in which the victim is authenticated.

  The purpose of a CSRF token is to mitigate CSRF attacks. It is a security measure implemented by web applications to protect against unauthorized actions performed by forged or malicious requests. The CSRF token is a unique value associated with a user's session or a particular action, and it is included in each request that modifies the application's state.
- What is the purpose of `form.hidden_tag()`?
  In web development using frameworks like Flask (Python) or Django (Python), the form.hidden_tag() function is typically used to generate a hidden input field in an HTML form. The purpose of the form.hidden_tag() function is to include a hidden input field in a form, which can be used to send additional data or flags along with the form submission.