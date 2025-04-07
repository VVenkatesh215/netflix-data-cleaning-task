# netflix-data-cleaning-task
This project involves cleaning and preprocessing a Netflix dataset. It includes handling missing values, removing duplicates, standardizing formats (like dates and text), renaming columns for consistency, and correcting data types using Python and Pandas.

In this project I performed essential data cleaning operations on a sample Netflix dataset using Python and Pandas.

## Dataset Overview:

The dataset contains information about Netflix shows including fields like:
- `show_id`
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `description`

## Cleaning Tasks Performed:

- Identified and handled missing values using `.isnull()` and filtering.
- Removed duplicate rows using `.drop_duplicates()`.
- Standardized text values such as country names.
- Converted date formats to a consistent `dd-mm-yyyy` format.
- Renamed columns to lowercase and removed spaces.
- Checked and fixed data types for consistency (e.g., `date_added` as datetime).

## Tools Used:

- Python
- Pandas
- Jupyter Notebook

## Files:

- `task.ipynb`: Jupyter Notebook containing all the cleaning steps and analysis 
- `netflix_cleaned.csv`: Cleaned version of the Netflix dataset 
- `amazon_prime_titles.csv`: Raw dataset used for reference 
- `task 1.pdf`:  Problem statement or task instructions |
- `README.md`: Project overview and file explanations

