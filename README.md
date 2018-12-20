# QueryCreatorVBA
This Query Creator uses VBA to build customized SQL queries based on user input.

The objective of this creator is to facilitate the reduce the amount of workhours spent querying the database by employees who need specific information but have no training in SQL/database structure. 

During my professional experience, I have noticed that many employees who need to access databases have no SQL training, which often makes retrieving information a needlessly long, frustrating, and overcomplicated process that wastes workhours and reduces morale. Consequently, I have designed a query creator that aims to cover the most commonly used SQL queries. 

I have designed the creator based on the Northwind database. Specifically, the target users of this creator belong to an imaginary Northwind team who works directly with suppliers, so the creator is limited to the tables that they would most often query, namely Orders, OrderDetails, Products, and Suppliers.

Please follow this link for the database structure: https://user-images.githubusercontent.com/45079274/50270597-5c9a4200-0432-11e9-9cd3-48dd46dc92cb.png

This project does not aim to cover all possible queries, and it shies away from the most complex ones. A notorious shortage is its inability to deal with NULL fields. However, as the intended user is virtually illiterate in SQL and NULL queries are intermediate/advanced level, such users will not be likely to attempt NULL queries nor any advanced ones.
