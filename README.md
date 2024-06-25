# NoSQL Database and Analysis Project

## Summary of the Assignment

This project involves setting up a NoSQL database, updating it with new data, and performing exploratory analysis using MongoDB and Jupyter Notebook. The goal is to assist a magazine, "Eat Safe, Love," in identifying noteworthy establishments based on their hygiene ratings and other criteria.

### Part 1: Database and Jupyter Notebook Set Up

1. **Import Data**: Imported the data from `establishments.json` into a MongoDB database named `uk_food`.
2. **Database Connection**: Verified the creation of the database and collection using PyMongo and Pretty Print.

### Part 2: Update the Database

- [NoSQL Database Setup and Update](NoSQL_setup_starter.ipynb)

1. **Add New Restaurant**: Added "Penang Flavours" to the database.
2. **Update Data**: Found and updated the `BusinessTypeID` for the new restaurant.
3. **Remove Establishments**: Deleted all establishments in the Dover Local Authority.
4. **Convert Data Types**: Converted latitude, longitude, and `RatingValue` to appropriate numeric types.

### Part 3: Exploratory Analysis

- [Exploratory Analysis](NoSQL_analysis_starter.ipynb)

1. **Which establishments have a hygiene score equal to 20?**
   - [image](images/hygiene_20.png)
   
2. **Which establishments in London have a `RatingValue` greater than or equal to 4?**
   - [image](images/london_rating.png)

3. **What are the top 5 establishments with a `RatingValue` of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?**
   - [image](images/top_five.png)

4. **How many establishments in each Local Authority area have a hygiene score of 0?**
   - [image](images/hygiene_zero.png)


### Resources

- MongoDB Documentation: [https://docs.mongodb.com/](https://docs.mongodb.com/)
- PyMongo Documentation: [https://pymongo.readthedocs.io/](https://pymongo.readthedocs.io/)
- Pandas Documentation: [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)
- ChatGPT by OpenAI for assistance with code and explanations



