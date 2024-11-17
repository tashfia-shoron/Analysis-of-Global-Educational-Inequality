### Technical Report: Analysis of Global Educational Inequality

### Analysis: https://github.com/tashfia-shoron/Analysis-of-Global-Educational-Inequality/blob/main/Analysis_of_Global_Educational_Inequality.ipynb

#### Objective
The objective of this analysis is to explore global educational inequality trends from 2010 to 2021, examining how disparities vary across countries and regions. By identifying key patterns and relationships, this report aims to shed light on the factors contributing to these inequalities and inform policy efforts to reduce them.

#### Dataset Overview
The dataset utilized in this analysis is titled *Inequality in Education Around the World*, encompassing historical data on educational inequality indicators from 2010 to 2021. The dataset includes 195 countries and features columns such as:

- **ISO3**: Country code.
- **Country**: Name of the country.
- **Human Development Groups**: Categorization by development level (e.g., Low, Medium, High, Very High).
- **UNDP Developing Regions**: Regional grouping (e.g., Sub-Saharan Africa (SSA), Latin America and the Caribbean (LAC)).
- **HDI Rank (2021)**: Human Development Index rank for 2021.
- **Inequality in Education (2010-2021)**: Yearly educational inequality scores.

#### Exploratory Data Analysis (EDA)
The dataset analysis began with an inspection of the data structure, types, and completeness. A heatmap visualized missing values, revealing incomplete data across several years for specific countries and columns.

##### Global Trends in Educational Inequality (2010-2021)
A line plot was used to depict the global average of educational inequality over the 12-year period. This visualization showed that while some fluctuation exists, there is a general downward trend, indicating improvements in educational access and quality in many parts of the world. The confidence interval represented by the shaded region displayed variations in inequality scores.

##### Regional Disparities in Educational Inequality (2021)
Two specific analyses were conducted for 2021:
1. **Box Plot by UNDP Regions**:
   - **Findings**: Sub-Saharan Africa (SSA) and South Asia (SA) regions displayed higher median educational inequality. In contrast, regions like Europe and Central Asia (ECA) had lower medians, indicating better education equity.
   - **Implications**: These findings highlight the need for focused educational interventions in lower-performing regions.

2. **Violin Plot by Human Development Groups**:
   - **Findings**: Countries in the "Low" human development group exhibited significant variability and higher median educational inequality. "Very High" development groups consistently had lower inequality scores, emphasizing the link between socioeconomic development and access to quality education.
   - **Implications**: Reducing educational disparities may require multi-faceted approaches that address broader social and economic inequalities.

##### Correlation Analysis: HDI Rank and Educational Inequality (2021)
A scatter plot was used to analyze the relationship between the 2021 HDI rank and educational inequality:
- **Observations**: Higher HDI-ranked countries (those with lower numerical values) generally had lower educational inequality. The scatter plot, with countries color-coded by region, illustrated that regions like SSA and SA clustered at higher inequality levels, while ECA and East Asia and the Pacific (EAP) tended to perform better.
- **Conclusion**: This analysis confirms that educational inequality is closely linked to a country's overall human development, suggesting that policies improving economic and social development can also lead to more equitable educational outcomes.

#### Insights and Key Observations
1. **Overall Improvement**: The global trend indicates progress, with many countries showing reductions in educational inequality over the past decade.
2. **Regional Disparities**: Sub-Saharan Africa and South Asia have the highest educational inequality, pointing to persistent challenges in access and quality. This underscores the importance of targeted educational investments and reforms.
3. **Impact of Development Level**: Countries classified under "Very High" human development consistently display lower educational inequality, suggesting that development and education are interlinked.
4. **HDI and Education**: The strong inverse relationship between HDI rank and educational inequality highlights the importance of integrated policy approaches that address both economic development and education.


#### Conclusion
The analysis provided a comprehensive overview of global educational inequality from 2010 to 2021, underscoring significant regional disparities and the role of human development. Addressing educational inequality requires holistic approaches that encompass not only educational policies but also broader socioeconomic development efforts.


### Reference

 - https://www.kaggle.com/datasets/iamsouravbanerjee/inequality-in-education-around-the-world/data
