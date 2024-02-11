

# Migration Patterns in Post-Conflict Regions

## Overview
Our project delves into understanding migration patterns within post-conflict regions, focusing on discerning patterns in internal and international migration. The primary objective is to comprehend the dynamics of displacement.

#
# Milestone 1: Problem Identification
**Date: 22-26 January, 2024**

You can find Planning documents for ouy group
including: group norms, learning goals, constraints, and a communication plan in the following link: 
  **Links to Planning Documents:**
  - [Group Norms](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/.collaboration/group_norms.md)
  - [Learning Goals](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/.collaboration/learning_goals.md)
  - [Constraints](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/.collaboration/constraints.md)
  - [Communication Plan](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/.collaboration/communication.md)


### Problem Statement
Our problem statement arises from personal experiences and observations of migration challenges in post-conflict regions. Barriers such as economic challenges, education hindrances, war-induced unsafe environments, and economic struggles contribute to the complex issue of migration dynamics.

### Understanding of the Problem Domain
Applying systems thinking and design thinking, our group recognizes migration's multi-faceted nature, considering factors like economic hardships, educational barriers, and the impact of war. This holistic understanding guides our exploration of migration patterns in post-conflict regions.

### Actionable Research Question
Building on our understanding, we pose the actionable research question:
**Research Question:** What are the discernible patterns in internal migration versus international migration within a post-conflict country, considering conflict data, socio-economic factors, and other relevant variables?
1. What are the main push factors influencing migration in the post-conflict region?
2. What are the main pull factors attracting individuals to migrate within or outside the post-conflict country?

## Objective
This project aims to identify patterns in internal migration versus international migration within post-conflict countries, emphasizing the dynamics of displacement.

## Dataset
Our analysis relies on datasets covering migration, conflict, and socio-economic factors.

## Scope and Region
The study analyzes migration patterns within a post-conflict country, considering both internal and cross-border movements.

## Reasons for Migration
Various factors contribute to migration in the post-conflict region, including minority status, economic challenges, education barriers, war, unsafe environments, economic struggles, underdeveloped country, economic hardships, and basic needs.

## Factors Influencing Immigrant Destination Choices
1. **Respect for Minorities:** Immigrants seek destinations that prioritize respectful treatment of minorities, valuing diversity and minimizing discrimination.

2. **Promising Future Prospects:** The allure of a better future drives immigrants to destinations offering personal and professional growth, education, career advancement, and economic stability.

3. **Citizenship Opportunities:** Prospects of obtaining citizenship motivate individuals, favoring countries with welcoming immigration policies and clear paths to citizenship.

4. **Geography and Culture:** Destination choices are influenced by geographical and cultural aspects, aligning with immigrants' preferences and values.

5. **Financial Opportunities:** Economic considerations play a crucial role as immigrants assess destinations based on financial opportunities, employment options, business prospects, and overall economic well-being.



# Milestone 2: Data Collection
## 29 January - 2 February, 2024

### Non-Technical Explanation of Domain Modeling
- **Approach:** Our data modeling approach involves incorporating a multidimensional analysis of migration patterns in post-conflict regions. We consider key factors such as socio-economic conditions, conflict dynamics, and demographic shifts. The choice is influenced by insights from domain experts, emphasizing both quantitative and qualitative data to capture the complexity of migration.

- **Possible Flaws:** While our approach is comprehensive, potential flaws may include challenges in quantifying certain qualitative aspects. Additionally, biases in available data sources could impact the accuracy of our models.


### Documentation for Data Set
Our dataset includes migration data from UNICEF, Our World in Data, Migration Data Portal, Eurostat, World Bank, Kaggle, and academic studies. The data covers migration patterns, conflict data, and socio-economic factors. you can find the detailed documentation here: 

- **Data Set:** [Link to Data Set](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/Data_cleaning)
- **Description:** The dataset includes the original MIMI dataset, cleaned versions, and additional data on countries of interest. The structure is documented in the cleaning.ipynb file, outlining the transformation process. Possible flaws, such as missing or incomplete data, are acknowledged.


### Data Collection and Cleaning Scripts
For transparency and replicability, all data collection and cleaning scripts are available in our directory, covering the entire process, including data separation into training and validation sets.

- [cleaning.ipynb](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Data_cleaning/cleaning.ipynb): Detailed script showcasing data cleaning procedures, handling missing values, and ensuring consistency.
- [countries_of_interest_data.csv](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Data_cleaning/countries_of_interest_data.csv): Script specifically addressing additional data on countries of interest.

### Public Hosting of Prepared Data Set (Work in Progress)
Our team is diligently working on the finalization of the prepared dataset, conducting thorough checks and implementing refinements. The dataset, currently in the [Data_cleaning](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/Data_cleaning) directory within our GitHub repository, is undergoing continuous improvements to ensure accuracy and completeness.

This ongoing process reflects our commitment to delivering a high-quality dataset. We appreciate your patience and understanding as we strive to provide a finalized version that meets the highest standards for transparency and replicability.



# Milestone 3: Data Analysis
## 5-16 February, 2024

### Non-Technical Explanation
In our analysis, focusing on the selected countries of interest (referenced below), we observed distinct migration patterns over the five-year period (2014-2019).

**Possible Sources of Error:**
- Variability in data reporting among countries.
- Incomplete or missing data for specific regions.
- Economic factors influencing migration might not be fully captured.


### Technical Description
Our analysis leveraged EuroStat (ESTAT) and UN datasets, focusing on the 2014-2019 period. We want to integrate GDP data from the World Bank for a comprehensive perspective. Selection of columns followed previous suggestions, incorporating neighboring countries' information.

**Techniques Used:**
- Descriptive statistics to understand migration patterns.
- Comparative analyses to identify regional disparities.
- Time-series analysis to discern temporal trends.

**Possible Flaws:**
- Reliance on aggregated data, potentially masking nuanced patterns.
- Economic indicators might oversimplify complex migration motivations.


### Replication Scripts and Documentation
All scripts and documentation for replicating our analysis are available in our [Data Analysis](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/Data_Analysis) directory. This includes detailed explanations, code snippets, and necessary datasets.

*Note: Analysis is ongoing; updates and refinements will be reflected in subsequent milestones.*

## Countries of Interest:
- Afghanistan
- Lebanon
- Libya
- Iraq
- Syria
- Yemen
- Sudan
- South Sudan
- Somalia
- Ukraine (conflict escalated in 2014)
- Democratic Republic of Congo
- Ivory Coast (Côte d'Ivoire)
- Sri Lanka
- Bosnia and Herzegovina
- Kosovo
- Chechnya (part of the conflict in Russia)
- Colombia
- Northern Ireland (The Troubles, though largely resolved by 2011)
- Myanmar
- Sierra Leone
- Liberia
- Eritrea
- Ethiopia (various conflicts, including the Ethiopian Civil War)
- Chad
- Burundi
- Angola
- Mozambique
- Sri Lanka



