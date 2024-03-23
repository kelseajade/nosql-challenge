# nosql-challenge
In Part 1 of the challenge, the focus is on establishing the connection between the MongoDB database and the Jupyter Notebook environment. This begins with importing the provided data from the establishments.json file into MongoDB, assigning the database the name "uk_food," and the collection the name "establishments." Once the data is imported, the notebook is prepared by importing necessary libraries, PyMongo for MongoDB and Pretty Print. An instance of the MongoClient is created to connect to the MongoDB server.  A single document from the establishments collection is retrieved and displayed using the find_one method.

In Part 2, modifications are made to the database. These modifications include adding a new restaurant named "Penang Flavours" in Greenwich, finding and updating the BusinessTypeID for "Restaurant/Cafe/Canteen," removing 994 establishments in Dover from the database, and converting number values from strings using update_many.

Part 3 focuses on analysis of the database. Questions involve querying the database to find establishments that meet criteria such as hygiene score, rating value, and geographical location. Each question is addressed by first querying the database, then displaying the results using count_documents and pprint for the first document, followed by converting the results to a Pandas DataFrame. 





