# The Art of Data Cleaning: The Power of Pandas With Real World Scenario
This project encompasses a real-world example of data analysis and cleaning carried out using the Pandas library in the Python programming language

# Project Description
Within the scope of the project, a series of operations were performed on two different datasets containing population and address data of the Netherlands. The key features of Pandas and commonly used methods for data loading, exploration, cleaning, and analysis steps are demonstrated.

## Data Description
### Population.csv:
  The population dataset contains population data for the years 2019, 2020, 2021, 2022, and 2023 for the Netherlands. The columns in your dataset are as follows:
  
  <li>postcode: Postal code<br>
  <li>year: Year<br>
  <li>total: Total population<br>
  <li>with_migration_background: Total population with migration background<br>
  <li>of_dutch_origin: Population of Dutch origin<br>
  <li>of_western_migration_origin: Population of Western migration origin<br>
  <li>afrika: Population of African origin<br>
  <li>amerika: Population of American origin<br>
  <li>asia: Population of Asian origin<br>
  <li>europe_excluding_dutch_background: Population of European origin excluding Dutch background<br>
  <li>oceania: Population of Oceania origin<br>
  <li>belgium: Population of Belgian origin<br>
  <li>germany: Population of German origin<br>
  <li>indonesia: Population of Indonesian origin<br>
  <li>morocco: Population of Moroccan origin<br>
  <li>former_dutch_antilles_aruba: Population of former Dutch Antilles and Aruba origin<br>
  <li>poland: Population of Polish origin<br>
  <li>suriname: Population of Surinamese origin<br>
  <li>turkey: Population of Turkish origin<br>
  <li>other_western_migration_background: Population of other Western migration origin<br>
    
### Nederlands.cvs:
  The Dutch dataset contains address information for the Netherlands. The columns in your dataset are as follows:<br>
  
  <li>PC6: Postal code.<br>
  <li>Buurt2023: The neighborhood code for the year 2023.<br>
  <li>Wijk2023: The district code for the year 2023.<br>
  <li>Gemeente2023: The municipality code for the year 2023.<br>

## Used Methods and Their Descriptions

### Data Reading and Loading:
  `read_csv`: This method is used to read a file containing comma-separated values (CSV). It is commonly used to load data into a Pandas DataFrame.
  
### Data Description:
  `shape`:This attribute that returns the dimensions (number of rows and columns) of a DataFrame. This attribute is used to understand the shape of the DataFrame and obtain information about the overall size of the dataset.<br>
  `.columns`:This attribute that contains the column names of a DataFrame. This attribute is used to access the column names within the DataFrame.<br>
  `.dtypes`: An attribute that returns a Series (Series) object containing the data types of the columns in a Pandas DataFrame. This attribute is used to check and analyze the data type of each column within the 
  DataFrame.<br>
  `info()`: This method that provides essential information about a Pandas DataFrame. This method offers insights into the general structure of the DataFrame<br>
  `describe()`: The method is a function that provides a basic statistical summary of the numerical columns in a DataFrame. It displays various statistical information related to numerical values in the dataset, 
  including measures such as mean, standard deviation, minimum, maximum, quartiles, and other relevant metrics.
  
### Handling Missing Data:
  `isna()` and `isnull()` : These methods is used for detecting missing values in a Pandas DataFrame.<br>
  `fillna()`: This method is used to fill missing values in a Pandas DataFrame with a specified value or strategy.<br>
  
### Data Filtering and Cleaning:
  `any()`: This method used to check if there is any True value in a Pandas DataFrame column. This method iterates over each column in the DataFrame and returns True as the result if it finds at least one True value in any item; otherwise, it returns False.<br>
  `loc`: loc een indexing operator used for label-based indexing in a Pandas DataFrame. This operator allows us to select specific rows and columns using their labels.<br>
  `iloc`: iloc an indexing operator used for position-based (integer-location-based) indexing in a Pandas DataFrame. This operator allows you to select specific rows and columns in a DataFrame using their positions (integer indices).<br>
  `isin()`: This method is a method used to compare values with values in a specific list or array.<br>
  `drop()`: This method is used to remove specified rows or columns.<br>
  `drop_duplicates()`: This method is used to remove duplicated rows.<br>
  `reset_index()`: This method is used to reset the index.<br>

### Data Manipulation:
  `.nunique()`:Thismethod in Pandas that returns the number of unique (distinct) values in the columns of a DataFrame. This method is commonly used to understand the count of unique values in each column of a DataFrame.<br>
  `select_dtypes`: This method used to select columns of a Pandas DataFrame with specific data types. This method is employed to filter columns with specific data types and restrict your DataFrame to the desired data types.<br>
  `str.replace()`: This method is used to replace a specific pattern or substring with another pattern or substring in each element of a Pandas Series.<br>
  `str.extract()`: This method is used to extract a specific pattern from each element of a Pandas Series. This method is commonly used to extract information within a string using regular expressions or another pattern.<br>
  `duplicated()`: This method is used to check whether an element is duplicated by a previous element.
  
### Data Type Conversions:
  `astype()`: This method is used to convert the data type of a Pandas Series.<br>
  
### Data Merging:
  `merge()`: This method is used to perform a merge operation between two or more Pandas DataFrames.<br>

## How to Run
To run the project, you need Python and Jupyter Notebook environment. Clone <a href="https://github.com/EmrullahCelk/The_Art_of_Data_Cleaning_The_Power_of_Pandas.git">the project</a>  files to your computer and run the project by installing the necessary dependencies. Additionally, you can view the project steps and results in the (Data_Cleaning.ipynb) file

## License
This project is licensed under the MIT License.
