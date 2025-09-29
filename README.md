# Elevate Labs Task 5
# Exploratory Data Analysis (EDA) on Titanic Dataset  

## Project Overview  
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to extract meaningful insights using **Python (Pandas, Matplotlib, Seaborn)**.  
The analysis focuses on understanding survival patterns based on different attributes like age, sex, class, fare, and family relations.  

## Objectives  
- Explore dataset structure and summary statistics  
- Analyze distributions of key features  
- Identify relationships and correlations among variables  
- Visualize survival trends across passenger demographics  
- Provide insights and summary findings  

## Tools & Libraries  
- **Python 3.x**  
- **Pandas** → Data manipulation & summary statistics  
- **Matplotlib** → Plotting  
- **Seaborn** → Advanced visualizations  

## Dataset Attributes  
- `survival`: Survival (0 = No, 1 = Yes)  
- `pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- `sex`: Gender  
- `age`: Age in years  
- `sibsp`: # of siblings/spouses aboard  
- `parch`: # of parents/children aboard  
- `ticket`: Ticket number  
- `fare`: Passenger fare  
- `cabin`: Cabin number  
- `embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

## Exploratory Steps  

1. **Data Exploration**  
   - `.info()`, `.describe()`, `.value_counts()` for initial checks  

2. **Univariate Analysis**  
   - Countplots of survival, class, gender, embarked port  
   - Histogram of age distribution  

3. **Bivariate Analysis**  
   - Survival rate across gender and class  
   - Boxplots of age vs survival  
   - Scatterplot of age vs fare colored by survival  

4. **Multivariate Analysis**  
   - Pairplot for survival, class, age, fare, sibsp, parch  
   - Heatmap for correlation matrix  

5. **Insights & Findings**  
   - Higher survival rates observed among females and 1st class passengers  
   - Younger passengers had better survival chances  
   - Fare shows positive correlation with survival (wealthier passengers survived more)  
   - Family relations (sibsp, parch) had mixed effects on survival  

## Visualizations Produced  
- Countplots  
- Histograms  
- Boxplots  
- Scatterplots  
- Pairplot  
- Heatmap  

## Deliverables  
- **Google Colab** → Code & visualizations  
- **PDF Report** → Observations & summary findings
