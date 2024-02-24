

# Migration Patterns in Post-Conflict Regions

## Overview
Our project delves into understanding migration patterns within post-conflict regions, focusing on international migration. The primary objective is to comprehend the dynamics of displacement.

## Milestone 1: Problem Identification
**Date: 22-26 January, 2024**

You can find Planning documents for ouy group
including: group norms, learning goals, constraints, and a communication plan in the following link: 
  **Links to Planning Documents:**
  - [Group Norms](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/.collaboration)
  - [Learning Goals](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/.collaboration)
  - [Constraints](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/.collaboration)
  - [Communication Plan](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/.collaboration)



### Problem Statement
Our problem statement arises from personal experiences and observations of migration challenges in post-conflict regions. Barriers such as economic challenges, education hindrances, war-induced unsafe environments, and economic struggles contribute to the complex issue of migration dynamics.

### Understanding of the Problem Domain
Applying systems thinking and design thinking, our group recognizes migration's multi-faceted nature, considering factors like economic hardships, educational barriers, and the impact of war. This holistic understanding guides our exploration of migration patterns in post-conflict regions.

### Actionable Research Question
Building on our understanding, we pose the actionable research question:
**Research Question:** What are the discernible patterns in international migration within a post-conflict country, considering conflict data, socio-economic factors, and other relevant variables?
1. What are the prevailing trends in migration within the post-conflict region, taking into account for international movements?
2. To what extent does the Gross Domestic Product (GDP) influence destination selection during migration within the post-conflict context?
3. Which specific countries do individuals from the post-conflict region tend to choose as their destination during migration, and are there discernible patterns in these choices?


## Objective
This project aims to identify patterns in international migration within post-conflict countries, emphasizing the dynamics of displacement.


## Factors Influencing Immigrant Destination Choices
Various factors contribute to migration in the post-conflict regions, including minority status, economic challenges, education barriers, war, unsafe environments, economic struggles, underdeveloped country, economic hardships, and basic needs.
1. **Respect for Minorities:** Immigrants seek destinations that prioritize respectful treatment of minorities, valuing diversity and minimizing discrimination.

2. **Promising Future Prospects:** The allure of a better future drives immigrants to destinations offering personal and professional growth, education, career advancement, and economic stability.

3. **Citizenship Opportunities:** Prospects of obtaining citizenship motivate individuals, favoring countries with welcoming immigration policies and clear paths to citizenship.

4. **Geography and Culture:** Destination choices are influenced by geographical and cultural aspects, aligning with immigrants' preferences and values.

5. **Financial Opportunities:** Economic considerations play a crucial role as immigrants assess destinations based on financial opportunities, employment options, business prospects, and overall economic well-being.


### Milestone 1 Retrospective
[Retrospective-01](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Retrospective/retrospective-01.md)

# Milestone 2: Data Collection
## 29 January - 2 February, 2024

### Non-Technical Explanation of Domain Modeling
- **Approach:** Our data modeling approach involves incorporating a multidimensional analysis of migration patterns in post-conflict regions. We consider key factors such as socio-economic conditions, conflict dynamics, and demographic shifts. The choice is influenced by insights from domain experts, emphasizing both quantitative and qualitative data to capture the complexity of migration.

- **Possible Flaws:** While our approach is comprehensive, potential flaws may include challenges in quantifying certain qualitative aspects. Additionally, biases in available data sources could impact the accuracy of our models, given that we could only find the dataset limited to Europe as a destination continent.

### Documentation for Data Set
Our dataset includes migration data from Eurostat, World Bank, and UN. The data covers migration patterns, conflict data, and socio-economic factors. you can find the detailed documentation here: 

- **Data Set:** [Link to Data Set](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/Data_cleanin)
- **Description:** This folder contains the files that includes the original MIMI dataset, cleaned versions, and additional data on countries of interest. The structure is documented in the cleaning.ipynb file, outlining the transformation process. Possible flaws, such as missing or incomplete data, are acknowledged.


### Data Collection and Cleaning Scripts
For transparency and replicability, all data collection and cleaning scripts are available in our directory, covering the entire process, including data separation into training and validation sets.

- [cleaning.ipynb](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Data_cleaning/cleaning.ipynb): Detailed script showcasing data cleaning procedures, handling missing values, and ensuring consistency.
- [countries_of_interest_data.csv](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Data_cleaning/countries_of_interest_data.csv): Script specifically addressing additional data on countries of interest.

### Public Hosting of Prepared Data Set (Work in Progress)
Our team is diligently working on the finalization of the prepared dataset, conducting thorough checks and implementing refinements. The dataset, currently in the [Data_cleaning](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/tree/main/Data_cleaning) directory within our GitHub repository, is undergoing continuous improvements to ensure accuracy and completeness.

This ongoing process reflects our commitment to delivering a high-quality dataset. We appreciate your patience and understanding as we strive to provide a finalized version that meets the highest standards for transparency and replicability.

 ### Milestone 2 Retrospective
[Retrospective-02](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Retrospective/retrospective-02.md)

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

### Milestone 3 Retrospective
[Retrospective-03](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Retrospective/retrospective-03.md)

## Milestone 4: Communicating Results
**19 February - 2 March, 2024**

### Target Audience Document

1. A document describing your target audience, their capabilities and constraints, their problem you are addressing, how you intend to reach them, and why they should “hire” you.
2. A communication artifact to achieve the goals in your document. Let your imaginations run with this! It could be a website, a powerpoint, a printed leaflet, a WhatsApp campaign ... anything, as long as you can justify why it’s the best way to reach them.


### Milestone 4 Retrospective
[Retrospective-04](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Retrospective/retrospective-04.md)


## Milestone 5: Final Presentation Event
**5-9 March, 2024**

1. A 1-minute pitch for your solution.
2. A 3-minute presentation of your group’s process from beginning to end including challenges you faced, lessons you learned, and any advice you have for future learners.
3. A retrospective for this milestone.

   
### Milestone 5 Retrospective
[Retrospective-05](https://github.com/MIT-Emerging-Talent/2024-group-07-cdsp/blob/main/Retrospective/retrospective-05.md)
