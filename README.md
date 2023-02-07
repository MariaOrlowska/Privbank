# Privbank
Project for CFG  Coding Kickstarter, Introduction to Data &amp; SQL

  PRIVBANK 


I  created database “Privbank” with 6 tables. They will store data about bank’s branches, branch employees, their salaries, positions, bonuses they can get for the sale of loans and the sales achieved.


tables:
branches
columns: ID_branch (PK), branch_city, number_of_employees
workers
columns: ID_worker (PK), surname, name, ID_branch (FK), ID_position (FK)
loans_granted
column: ID_loan (PK), ID_product (FK), loan_value, ID_worker (FK), Date_sale
products
columns: ID_product (PK), product_name, points_for_sale 
position
columns: ID_position, position_name, solary
bonuses:
columns: Id_bonus (PK), min_points, max_points, bonus_amount
