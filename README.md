# CHPC Summer School 2025: Working with Data in Python
This repository contains a Python script to process and analyze racing game data. The script demonstrates various data manipulation techniques, such as importing, cleaning, subsetting, and transforming data using the pandas library.

# Table of Contents
Overview
Installation
Usage
Code Explanation
Contributing
License
Overview
The script processes a dataset of racing game results stored in a CSV file, RacingGameData.csv. It demonstrates basic data operations, including:

# Importing data using pandas.
Exploring the data: checking variable names, number of observations, and data types.
Subsetting and filtering the dataset based on specific conditions.
Sorting and modifying variables.
Handling duplicated rows and recoding variables.

# Installation
Clone the repository:
```
git clone https://github.com/yourusername/chpc-summer-school-2025.git
```
Navigate to the project directory:

```
cd chpc-summer-school-2025
```

# Install the required packages:
```
pip install pandas
```
Make sure you have pandas installed in your Python environment to run the script.

# Usage
Modify the file path in the script to point to where the RacingGameData.csv file is located on your machine:
```
os.chdir(r"/path/to/your/data")
```
Run the Python script to process and analyze the data:
```
python racing_analysis.py
```
The script will output various analyses, such as the first few rows of the dataset, the number of rows and columns, sorted data, and more.

# Code Explanation
1. Data Import and Exploration
The dataset is imported using pandas.read_csv().
The first few rows of the data are displayed, and basic information such as the number of rows, columns, and data types is printed.
2. Data Subsetting and Filtering
The data is filtered by racing track type and engine type.
Specific rows are selected based on conditions, such as races on the "OvalTrack" or those with a "Bayes" engine.
3. Sorting Data
The data is sorted by "TopSpeedReached" and "FinishTime" in both ascending and descending orders.
4. Data Transformation
New variables are created based on existing columns, such as calculating the time it took to go from checkpoint 1 to checkpoint 2.
5. Recoding Variables
The variable CheckPoint2_66 is recoded to "Yes" or "No" based on its values.
6. Handling Duplicates
Duplicated rows are identified and removed, keeping only the first occurrence of each duplicated row.
Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvement, feel free to fork this repository and submit a pull request.

# Fork the repository
Create a new branch (git checkout -b feature-branch)
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature-branch)
Create a new Pull Request
License
This project is licensed under the MIT License - see the LICENSE file for details.

