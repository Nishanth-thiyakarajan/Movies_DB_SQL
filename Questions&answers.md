# Questions and solutions
-----------------------------------------------------------------------------------
Consider a scenario that you have joined the organization as a business analyst and you are asked to query the databasee to get some useful insights that will help the organization grow. Some of the members will ask you some inights from their perpective, we need to query the database and provide the results to them.

#Note : Please read the readme.md file to get the understanding of the data and its structure.
-----------------------------------------------------------------------------------

1.	We will need a list of all staff members, including their first and last names, 
email addresses, and the store identification number where they work.

SELECT 
	first_name, 
    last_name, 
	email, 
    store_id
FROM staff;
