# Titanic Dataset - Exploratory Data Analysis (EDA)
## Dataset
The dataset used is the classic **Titanic** dataset containing information on passengers such as:
- Age
- Sex
- Class
- Fare
- Embarkation Port
- Survival status

## Technologies Used
- Python 
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

## EDA Steps
### 1. Data Loading & Overview
- Loading CSV file using `seaborn`
- Viewing structure with `.info()`, `.head()`.

*Screenshot: 
![image](https://github.com/user-attachments/assets/9b95633d-ef2f-4d32-bd19-0898eed38bbf)


## Data Cleaning
 Dropped unnecessary column Deck 
 Filled missing values in:
- Age with mean
- Embarked with most value_counts()

Screenshot:

![image](https://github.com/user-attachments/assets/794e4326-93ab-4704-8277-d31895e6c66a)

## Univariate Analysis
## Plotted counts of:
- Survived
- Pclass
- Embarked
- Sex
## Age distribution with histogram

Screenshot:
![image](https://github.com/user-attachments/assets/f05955a5-fc7d-41b4-b64b-ddf304df16fa)
![image](https://github.com/user-attachments/assets/9bdfc439-9dc4-4f8b-b977-57042e1ae26c)


## Bivariate Analysis
## Compared survival based on:
- Sex
- Passenger class
- Age (via boxplots)

Screenshots:

![image](https://github.com/user-attachments/assets/473febef-8025-4ad0-89ef-862faa50a576)
![image](https://github.com/user-attachments/assets/ab58c6f1-7cfc-4410-81d1-a65e8e04d56a)


## Grouped Survival Analysis
The dataset was further analyzed to calculate mean survival rates across different categories:
- Females had a much higher survival rate across all classes, especially in 1st and 2nd class.
- Males, particularly in 3rd class, had the lowest survival probability.

Screenshots:

![image](https://github.com/user-attachments/assets/786eaf09-fd49-42e7-986a-394d10088925)
