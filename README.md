# Ames Housing Data Analysis
This is the ML Capstone Project for NYCDSA

There are the code and data files with description:

Data folder:
1. Ames_Housing_Price_Data.csv: This is the main source of data for EDA and Model Building, this dataset contains information about homes features and the target - “Sale Price”
2. Ames_Real_Estate_Data.csv: We used this data to get property zip code and tax assessment, which is public data and should be available at the time of prediction 
3. IA_Taxes.csv: This is the key file used for extracting IA income tax related features at zip code level. The file contains zip code and only the features that are needed for model.
4. IA_zip_tax_v2.csv: This file contains more details regarding tax information about IA taxes, and the file was used for EDA only. 
5. Tax_Data_Dictionary.xlsx: This is the data dictionary for taxes and how each feature was engineered.
6. data_description.txt: Overall data descriptions for Ames Housing Price features
7. housing.csv: This is the clean data with all the features ready for model building, if you are not interested in EDA you can use this directly to train models.

Code or Python Notebooks:
1. Part 1 - EDA Ames Housing Data.ipynb: This part of EDA focused on raw data and explores the housing features such as bedrooms, gross living area, price distribution etc.
2. Part 2 - EDA with Neighborhood Analysis.ipynb: This part of EDA looks at neighborhoods in Ames and how the prices could vary across neighborhoods.
3. Part 3 - Tax Features.ipynb: This notebook processes the income tax data by zip codes in Iowa (IA) 
4. Part 4 - Housing Data Preprocessing.ipynb: This the data cleaning and processing notebook, where all the dummy variables are created.
5. Part 5 - Model Building.ipynb: This notebook used H2O libraries to explore GBM and AutoML models.

EDA Using Tableau
There are two Tableau workbooks that have EDA for presentation:
1. "Housing EDA.twb" uses housing.csv to visualize clean processes data
2. "eda on tax - ames housing.twb" uses the tmp4.csv file, this was used to visualize tax data by zip code

Note that EDA was done using Python Notebooks, Tableau Desktop 2022.3 was used to visualize data for presentation purpose only.
