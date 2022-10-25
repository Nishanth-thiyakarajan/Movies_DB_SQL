# Questions & solutions
-----------------------------------------------------------------------------------
Consider a scenario that you have joined the organization as a business analyst and you are asked to query the databasee to get some useful insights that will help the organization grow. Some of the members will ask you some inights from their perpective, we need to query the database and provide the results to them.

#### Note : Please read the readme.md file to get the understanding of the data and its structure.
-----------------------------------------------------------------------------------

1. We will need a list of all staff members, including their first and last names, 
email addresses, and the store identification number where they work.

```SQL
SELECT 
	first_name, 
        last_name, 
	email, 
        store_id
FROM 
	staff;
```
This SQL query will return the all the staff members and their details from staff table.

Output:

![1](https://user-images.githubusercontent.com/71631641/197812663-db374ffa-1f52-4232-8c03-d5b8ac2fd034.jpg)
![alt text](http://url/to/img.png)
