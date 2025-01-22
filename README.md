# nosql-challenge: Eat Safe, Love: UK Food Standards Database Analysis

## **Overview**
This project involves using MongoBD and Python for database management and analysis related to the food hygiene ratings provided by the UK Food Standards Agency. The challenge covers:
1. Import the data into MongoDB, set up the database and collections, and verify the data using PyMongo and Jupyter Notebook.
2. Modify the database by adding new records, updating fields, removing unnecessary data, and cleaning inconsistent data types for accurate analysis.
3. Perform targeted queries and aggregation to analyze food hygiene ratings, identify trends, and answer key questions for the magazine. 

## **Technologies Used**
- MongoDB for storing, querying and managing the NoSQL Database
- Pandas for data manipulation and analysis 
- PPRINT for displaying JSON-like data in a clean and comprehensible format
- Jupyter Notebook for data exploration and analysis 
- CSV files of data input for MongoDB

nosql-challenge/
    NoSQL_analysis_starter.ipynb       # Jupyter Notebook for exploratory data analysis
│   NoSQL_setup_starter.ipynb          # Jupyter Notebook for database setup and updates
│   README.md                          # Project documentation (this file)
│   Resources/            
    └── establishments.json            # JSON data to import into MongoDB


## **Setup Instructions**
1. **Install the Dependencies:**
Ensure Pymongo and Pandas are installed 

2. **Import Data:**
Use the mongoimport command to import establishments.json into the uk_food database.

3. **Run Jupyter Notebook:**
Run the queries in jupyter for both NoSQL_analysis_starter and NoSQL_setup_starter for datasetup, updates and exploratory analysis.

4. **Verify Setup:** 
- Confirm the uk_food database and establishments collection exist using PyMongo. 
- Retrieve a sample document with find_one().
- Convert string fields for latitude, longitude, and RatingValue into numerical types using update_many().

5. **Perform Analysis:** 
Complete the exploratory analysis in NoSQL_analysis_starter.ipynb, including identifying establishments with a hygiene score of 20, London establishments with a RatingValue ≥ 4, and the nearest establishments to "Penang Flavours" with a RatingValue of 5.

6. **Export Results:** 
Save any DataFrame outputs to CSV files for documentation purposes.











