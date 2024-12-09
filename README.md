# Global-Emissions-Dataset-EDA
Portfolio Project for Sustainability - EDA on Global Emissions Dataset

# Project Overview
This project analyzes global methane emissions data from multiple sectors, focusing on emissions from regions, countries, and industry segments. The dataset includes 1548 entries, featuring variables such as emission type, segment, region, and country. Using Python, I performed data cleaning and exploratory data analysis (EDA) to uncover key patterns and trends. The analysis highlights the major contributors to methane emissions, with a particular focus on the energy sector, which dominates the dataset. Insights were drawn on the distribution of emissions across regions such as Africa, Europe, and Asia Pacific, as well as the role of specific emission types like Energy, Agriculture, and Waste. This work aims to provide actionable recommendations for reducing methane emissions and advancing sustainability efforts.
 
# Dataset Information
- Source: Kaggle
- Dataset: Global Emissions by ashishraut64
- License: Public Domain, The dataset is openly available for public use and analysis.

# Key Features
- Regions: The dataset contains emissions data across various global regions such as Africa, Europe, Asia Pacific, and others, with "World" representing global totals.
- Countries: Data includes emissions from over 100 countries, with "World" as an aggregated entry.
- Emissions: The emissions column represents the methane emissions in metric tons for each entry, with values ranging from very small amounts to several hundred thousand metric tons.
- Emission Types: The dataset categorizes emissions by types such as Energy, Agriculture, Other, and Waste, with Energy being the dominant contributor.
- Segments: Emissions are further broken down into specific segments within each sector, such as Onshore oil, Gas pipelines, Bioenergy, and Satellite-detected emissions.
- Reason: The dataset also indicates the reason for methane emissions, including categories like "All," "Fugitive," and "Vented."
- Base Year: The emissions data spans several years, from 2019 to 2022, reflecting different time periods for estimates and actual data.
This dataset offers a comprehensive view of global methane emissions, providing valuable insights for environmental analysis and sustainability efforts. It spans from 2019-2022.

# Tools and Technologies
- Programming Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, and Plotly

# Methodology
- Data Cleaning and Preparation -Removed missing values and standardized data formats & Verified consistency across emission categories.
- Exploratory Data Analysis (EDA) -Explored trends, distributions, and relationships between emission sources & Created visualizations to highlight key insights.

# Exploratory Questions and Answers for Sustainability Analysis
1. Which region has the highest total methane emissions?
Asia Pacific Region has the highest Emissions (kt).
2. How do methane emissions vary across regions?
Methane emissions vary significantly across regions, with higher emissions typically observed in areas with extensive agriculture and/or energy. Regions with less industrial activity or natural methane sources tend to have lower emissions.
3. Which country emits the highest and lowest methane?
The highest emissions is China and the lowest is Seychelles.
4. What are the top 5 countries contributing to global methane emissions?
China, United States, Russia, India and Brazil are the top 5 contributors to global methane emissions.
5. Which sector contributes the most/least to methane emissions?
The Energy section contributes to the most methane emissions and Other is the lowest contributer.
6. How are emissions distributed across sectors in high-emission countries?
Energy is the dominant sector contributing to emissions. For instance, China and India have the highest emissions in the Energy sector, while Agriculture is the largest contributor in Brazil and India. The Waste sector also contributes significantly, especially in countries like Brazil and the United States.
7. Are there correlations between specific segments and reasons for emissions?
Yes, certain activities are linked to specific types of methane emissions. For instance, "Steam Coal" produces the most overall emissions, while "Offshore Oil" and "Onshore Oil" create the most methane from burning gas, and "Gas Pipelines and LNG Facilities" lead to the highest amount of methane released intentionally.
8. What are the most common reasons for methane emissions?
The most common reasons for methane emissions in the dataset are "All," which occurs 746 times, followed by "Fugitive" and "Vented," both occurring 342 times, and "Flared," which occurs 118 times.
9. Which sub-sector has the largest emissions globally?
The sub-sector with the largest emissions globally is energy

# Results and Recommendations
- The Energy sector is by far the largest contributor to global methane emissions. This includes emissions from oil and gas extraction, pipelines, and other energy-related activities. Given that Energy accounts for over 75% of the emissions, it's clear that addressing emissions from this sector will have the largest impact on reducing overall methane emissions.
- A significant portion of methane emissions comes from the Agriculture sector, particularly in developing countries where agriculture plays a key role in the economy. The Waste sector also contributes notably, especially with emissions from landfills and waste treatment facilities.
- Fugitive vs. Vented Emissions: The analysis of emission types reveals that Fugitive emissions (those accidentally released, such as from leaks in oil and gas infrastructure) and Vented emissions (intentionally released from energy infrastructure) are major contributors. The dataset shows that a large portion of methane emissions come from these two categories, emphasizing the need for better management and capture technologies.
- Disproportionate Contribution from Few Countries: While emissions are spread globally, a few countries (especially large emitters like the United States, Russia, and China) account for a disproportionate share of the total emissions. Focusing on emissions reduction in these countries could yield significant global reductions.
- Recommendations for Action: To reduce methane emissions globally, efforts should focus on the Energy sector, specifically targeting fugitive emissions from oil and gas infrastructure, improving technologies and increase investment in renewable energy to curb emissions from fossil fuels. 


# Limitations
- Temporal Coverage: The dataset is limited to specific years, restricting long-term trend analysis.
- Data Completeness: Missing data for certain regions may lead to underrepresentation.
- Focus on Methane: While methane is critical, other greenhouse gases were not analyzed in this project.

# References
- Dataset: Global Emissions
- Kaggle License: Public Domain

