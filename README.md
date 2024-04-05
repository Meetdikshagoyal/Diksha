## YouTube Channel Analysis

### Project Title
This project involves analyzing YouTube channel data to understand the distribution of channel types and performing database operations to store and manipulate the data.

### Getting Started
#### Prerequisites
Make sure you have the following installed:

- **Python** (version 3.0 or higher)
- **Pandas**
- **Matplotlib**
- **pymysql**
- **sqlalchemy**

### Installing
You can install the required Python libraries using pip:

```bash
pip install pandas matplotlib pymysql sqlalchemy
```

### Running the Tests
#### Breakdown of Tests
1. **Data Extraction**: The provided code reads a CSV file containing YouTube channel data.
2. **Data Filtering**: It filters the dataframe to select the first 1000 rows and the first 3 columns.
3. **Data Analysis**: The code calculates and visualizes the distribution of channel types from the top 1000 records.
4. **Data Export**: It exports the filtered data to a CSV file named "top_1000_youtube_channels.csv".
5. **Database Connection**: The code connects to a MySQL database and creates a new database named "Youtube".
6. **Data Loading**: It loads the filtered data into a table named "youtube_channels" in the MySQL database.

### Deployment
To deploy the code, follow these steps:
1. Download the Python script and the dataset provided by Professor Omar Al Trad.
2. Update the file paths and database connection details as needed.
3. Run the script in a Python environment.

### Author
This project was developed by **Diksha Goyal**.

### License
This project is licensed under the **MIT License** - see the LICENSE file for details.

### Acknowledgement
Special thanks to **Professor Omar Al Trad** for providing the dataset and lectures that helped in coding. I would also like to acknowledge the assistance of my group member, **Kavleen Kaur**, in writing the code.
