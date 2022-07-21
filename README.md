# Design-and-create-a-Relational-Database-Table-Using-SQLiteStudio
We'll use SQLiteStudio in this project because it's free, and it contains everything required for our purposes.
We'll be working with database of a fictitious veterinary clinic.
- We will create a database called 'PetVet' and store it in the following directory: C:/Users/vu/Databases/PetVet.db
- Connect to the database created, reach up to structure option and select 'Create a table'
![image](https://user-images.githubusercontent.com/101500579/180199849-99e8af8d-b825-45d5-9640-4c32388748fa.png)

Now, there're something to keep in mind when creating tables in a relational database:
- A table contains data that describes ONE entity
- Table name is unique inside the database
- Columns, also called fields or elements, have unique names inside the table 
- Columns have data types that determine the kind of data that they hold (numbers, letters, etc)
- Rows, also called tuples, are uniquely identified by one or more fields that make up a primary key

Next, we will create a table called 'Pet' with the primary key is PetId
![image](https://user-images.githubusercontent.com/101500579/180203015-8b3b7b61-770f-447d-a253-8051934769f9.png)

Create some more columns for PetName, BirthDate, BirthDate, PetType

![image](https://user-images.githubusercontent.com/101500579/180204563-4baf4784-2e9d-4558-aca2-309cf2da45d1.png)
![image](https://user-images.githubusercontent.com/101500579/180204922-8a380d38-c49c-48cb-8fdd-28e7759bd109.png)
![image](https://user-images.githubusercontent.com/101500579/180205353-07e61409-e9b9-4df6-a852-c672f740323a.png)
![image](https://user-images.githubusercontent.com/101500579/180206060-1644e3f2-f94a-440d-b666-6d3766c2379f.png)

Now, let's add some data to our table. There are some issues to consider when adding data to a table
- Where is the data coming from? Paper, another database, live transactions?
- What is the volume of data to be added? How often?
- Is the existing data in the same format as the database table?
- Will programming be required or can the data be entered manually?

In this project, I will just demonstrate some manual data entries in SQLiteStudio

Navigate to the data tab, click the green plus sign
![image](https://user-images.githubusercontent.com/101500579/180208546-c8511eaa-8b38-4215-96f5-b602c5808d70.png)

Click commit to save 2 newly added records
![image](https://user-images.githubusercontent.com/101500579/180209535-03b2b1a4-f9ee-4efe-b408-80b6c7a60e78.png)

If we want to commit changes for records that have the same PetId for ones added, an error prompt will appear in the status bar.

![image](https://user-images.githubusercontent.com/101500579/180209796-5b4b5d28-0e5c-47b1-8fa7-71b6e31078a0.png)

To fix that, we just need to enter a different PetId


