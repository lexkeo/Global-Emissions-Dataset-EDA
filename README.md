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

# Exploratory Questions for Sustainability Analysis
1. Which region has the highest total methane emissions?
2. How do methane emissions vary across regions?
3. Which country emits the highest and lowest methane?
4. What are the top 5 countries contributing to global methane emissions?
5. Which sector contributes the most/least to methane emissions?
6. How are emissions distributed across sectors in high-emission countries?
7. Are there correlations between specific segments and reasons for emissions?
8. What are the most common reasons for methane emissions?
9. Which sub-sector has the largest emissions globally?

# Results and Recommendations
- Dominance of the Energy Sector: The Energy sector is by far the largest contributor to global methane emissions. This includes emissions from oil and gas extraction, pipelines, and other energy-related activities. Given that Energy accounts for over 75% of the emissions, it's clear that addressing emissions from this sector will have the largest impact on reducing overall methane emissions.
- Regional Emissions Distribution: The dataset shows that Africa is the largest regional contributor to methane emissions, followed by Europe and Asia Pacific. Africa, with its significant agricultural activity and increasing energy demands, plays a central role in the emissions landscape. Meanwhile, countries in Europe and Asia Pacific are major contributors, largely due to their advanced energy industries.
- Sector-Specific Emissions: A significant portion of methane emissions comes from the Agriculture sector, particularly in developing countries where agriculture plays a key role in the economy. The Waste sector also contributes notably, especially with emissions from landfills and waste treatment facilities.
- Fugitive vs. Vented Emissions: The analysis of emission types reveals that Fugitive emissions (those accidentally released, such as from leaks in oil and gas infrastructure) and Vented emissions (intentionally released from energy infrastructure) are major contributors. The dataset shows that a large portion of methane emissions come from these two categories, emphasizing the need for better management and capture technologies.
- Emission Trends Over Time: The dataset spans several years (2019-2022), revealing fluctuations in emission levels. These fluctuations likely reflect both actual changes in emission sources (such as industrial activity or policy changes) and estimations in sectors where data is harder to track (like satellite-based emissions for large-scale oil and gas fields).
- Disproportionate Contribution from Few Countries: While emissions are spread globally, a few countries (especially large emitters like the United States, Russia, and China) account for a disproportionate share of the total emissions. Focusing on emissions reduction in these countries could yield significant global reductions.
- Recommendations for Action: To reduce methane emissions globally, efforts should focus on the Energy sector, specifically targeting fugitive emissions from oil and gas infrastructure, improving technologies and increase investment in renewable energy to curb emissions from fossil fuels. 


# Limitations
- Temporal Coverage: The dataset is limited to specific years, restricting long-term trend analysis.
- Data Completeness: Missing data for certain regions may lead to underrepresentation.
- Focus on Methane: While methane is critical, other greenhouse gases were not analyzed in this project.

# References
- Dataset: Global Emissions
- Kaggle License: Public Domain

