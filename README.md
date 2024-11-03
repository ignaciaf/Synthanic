# Survival Analysis of Shipwreck Passengers

## Project Overview
This project analyzes a synthetic dataset based on the Titanic to study factors that influenced passenger survival. The analysis focuses on the relationship between passenger class, gender, and survival likelihood, using Python tools like **Pandas**, **Seaborn**, and **Matplotlib**.

## Dataset
The dataset used includes information about passengers, such as:
- **Pclass**: Passenger class (1 = First Class, 2 = Second Class, 3 = Third Class)
- **Sex**: Passenger gender
- **Survived**: Survival status (1 = Survived, 0 = Did not survive)

This data allows for exploring survival patterns based on various demographic variables.

## Exploratory Analysis
Throughout the analysis, several charts and visualization techniques were used to identify survival patterns among specific passenger groups:
1. **Point Plot**: Displays survival rates by class and gender, highlighting gender differences within each class.
2. **Stacked Bar Chart**: Shows the proportion of survivors within each class.

## Key Findings
The most significant conclusion from the analysis is:
- **Women in first class had a higher likelihood of survival compared to other groups**. This observation may partly be explained by evacuation priorities and available resources on the ship. In particular:
  - First-class women had a significantly higher survival rate than men in any class.
  - The survival rate for women decreases in second and third class but remains higher than that of men.

These results suggest a trend of greater protection for women and first-class passengers during the evacuation process.

## Technologies Used
- **Python**
- **Pandas** for data manipulation and cleaning
- **Seaborn** and **Matplotlib** for data visualization

## Project Usage
You can explore this analysis by downloading the `ipynb` file and running it in a Jupyter Notebook environment. Be sure to install the required libraries:
```bash
pip install pandas seaborn matplotlib
