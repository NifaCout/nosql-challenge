# nosql-challenge
NoSql challenge
Part 1 file: Database and Jupyter Notebook Set Up.
  1.	Import the data provided in the establishments.json file from your Terminal.
  2.	Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).
  3.	Create an instance of the Mongo Client.
  4.	Confirm that you created the database and loaded the data properly.
  5.	Assign the establishments collection to a variable to prepare the collection for use.
Part 2: Update the Database.
  1.  Add the provided information regarding new restaurant to the database.
  2.  Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
  3.  Update the new restaurant with the BusinessTypeID you found
  4.  Some of the number values are stored as strings, when they should be stored as numbers.
        Use update_many to convert latitude and longitude to decimal numbers.
        Use update_many to convert RatingValue to integer numbers.
Part 3: Exploratory Analysis on four main questions. 
  1.  query is correctly performed to find the establishments with a hygiene score of 20.
  2.  Which establishments in London have a RatingValue greater than or equal to 4.
  3.  What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
  4.  How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten 
      local authority areas. 
     a. count_documents() is used to list the correct number of documents.
     b. the first result is printed using pprint.
     c. The results are converted to a Pandas DataFrame and displays the first 10 rows.
