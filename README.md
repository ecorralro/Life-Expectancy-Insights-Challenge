# Life-Expectancy-Insights-Challenge

## 📋 Overview
Welcome to the **Life Expectancy Insights** competition! Your task is to predict the life expectancy of individuals based on various health, demographic, and socio-economic factors. This challenge provides an opportunity to explore real-world datasets and apply your data science and machine learning skills to uncover patterns that influence life expectancy.

---

## 📖 Description
Understanding life expectancy is a critical step in addressing global health and socio-economic challenges. By analyzing patterns and relationships in data, we can gain insights that inform policy, healthcare strategies, and social initiatives.

### What is Life Expectancy?
Life expectancy refers to the average number of years a person is expected to live based on current mortality rates. It is influenced by a wide range of factors, including:

- **Health conditions**: Immunization coverage, prevalence of diseases, and access to healthcare.
- **Demographic features**: Age, gender, and population metrics.
- **Socio-economic conditions**: Education levels, income, and living standards.

Accurately predicting life expectancy helps governments, organizations, and researchers identify areas of intervention and allocate resources effectively.

---

## 🧮 Evaluation
Submissions for this competition will be evaluated based on the **R² (Coefficient of Determination)** metric. This metric assesses how well your model's predictions align with the actual values. 

- **R² value closer to 1**: Indicates a better fit, meaning your model explains most of the variance in the data.

---

## 📊 Columns

### General Information
- **Unnamed: 0**: Index of the row.
- **Country**: Name of the country.
- **Year**: Year of observation.
- **Status**: Development status of the country (Developed or Developing).

### Health Indicators
- **Adult Mortality**: Probability of dying between 15 and 60 years per 1000 population.
- **Infant deaths**: Number of infant deaths per 1000 population.
- **Alcohol**: Per capita alcohol consumption (in litres).
- **Percentage expenditure**: Expenditure on health as a percentage of GDP.
- **Hepatitis B**: Percentage of people immunized against Hepatitis B.
- **Measles**: Number of reported cases of measles per 1000 population.
- **BMI**: Average body mass index of the population.
- **Under-five deaths**: Number of deaths of children under five years old per 1000 population.
- **Polio**: Percentage of people immunized against Polio.
- **Total expenditure**: Total expenditure on health as a percentage of GDP.
- **Diphtheria**: Percentage of people immunized against Diphtheria.
- **HIV/AIDS**: Deaths per 1000 population caused by HIV/AIDS.

### Economic and Population Metrics
- **GDP**: Gross Domestic Product per capita (in USD).
- **Population**: Population of the country.
- **Thinness 1-19 years**: Prevalence of thinness among individuals aged 10-19 years (%).
- **Thinness 5-9 years**: Prevalence of thinness among individuals aged 5-9 years (%).
- **Income composition of resources**: Human development index in terms of income composition.
- **Schooling**: Average number of years of schooling.

### Target Variable
- **Life expectancy**: The target variable representing the predicted life expectancy of the population (in years).
