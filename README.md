# Road-Traffic-Accidents

# Driving Insights: An In-Depth Exploration of Road Traffic Accident Patterns

![360_F_726800565_rBmlNz0EdAAizWPBOKbY54ZelCetFC1P](https://github.com/user-attachments/assets/604b9bf5-38d5-4f6c-acf4-ead84507ef97)


# Introduction
This report presents a comprehensive analysis of road traffic accidents in Addis Ababa. I analyzed a dataset downloaded from `Kaggle` to reveal critical insights that could contribute to improving road safety initiatives. The dataset encompasses a wide range of factors, including driver demographics, vehicle types, road conditions, and accident causes. 

# Objective
The objective of this analysis is to uncover key patterns and trends that can inform strategies to enhance road safety and reduce the incidence of accidents.

# Dataset Overview
- Total Records: 12,316
- Columns: 25

The dataset was carefully preprocessed to ensure accuracy and relevance:
- The `Time` column was converted to a datetime format to facilitate time-based analysis.
- Rows containing missing values were removed to maintain the integrity of the analysis.
- Irrelevant columns, such as `Sex_of_casualty` and `Casualty_class`, were deleted.
- Categorical variables like `Driving_experience` and `Age_band_of_driver` were mapped to numerical values for correlation analysis.

# Key Findings

**Most Common Day for Accidents**
- Day: Friday
- Accident Count: 644

Friday was identified as the most accident-prone day of the week, which may be attributed to increased traffic as people prepare for the weekend.

**Age Band of Drivers Involved in Accidents**
- Most Common Age Band: 18-30 years
- Accident Count: 1,387

Drivers aged 18-30 are the most frequently involved in accidents, potentially due to their relative inexperience and higher likelihood of engaging in risky driving behaviors.

**Type of Vehicle Involved**
- Automobiles: 1,111 accidents
- Lorries (41-100Q): 829 accidents

Automobiles are the most common vehicles involved in accidents, followed by lorries. This indicates a need for targeted interventions to improve safety in these vehicle categories.

**Gender Distribution in Accidents**
- Male Drivers: 3,707 accidents
- Female Drivers: 218 accidents
- Unknown: 53 accidents

Male drivers are disproportionately involved in accidents compared to female drivers, which reflects broader driving patterns and potentially more aggressive driving behavior among males.

**Common Causes of Accidents**
- No Distancing: 752 accidents
- Changing Lane to the Right: 584 accidents
- Driving Carelessly: 485 accidents

Maintaining a safe following distance and lane discipline are critical issues that need to be addressed through stricter enforcement and driver education programs.

**Educational Level of Drivers**
- Junior High School Education: 2,655 accidents

The analysis revealed that drivers with a junior high school education level are most commonly involved in accidents, suggesting a potential gap in road safety education at this level.

**Peak Hours for Accidents**
- 5:00 PM: 403 accidents

The peak time for accidents is during the evening rush hour, particularly at 5:00 PM, highlighting the dangers associated with high traffic volumes during this period.

**Weather Conditions During Accidents**
- Normal Weather: 3,239 accidents
- Rainy Weather: 444 accidents

While most accidents occur under normal weather conditions, rainy weather still presents a significant risk, underscoring the importance of driving cautiously in adverse conditions.

**Road Surface Type**
- Asphalt Roads: 3,719 accidents

The majority of accidents occur on asphalt roads, the most common type of road surface in urban areas, indicating a need for ongoing maintenance and potential improvements to these surfaces.

**Correlation Analysis**
- Driving Experience: Drivers with 5-10 years of experience are the most involved in accidents.
- Age vs. Number of Vehicles: A slight negative correlation was found between the driver’s age and the number of vehicles involved in an accident.

# Conclusion
This analysis sheds light on the critical factors contributing to road traffic accidents in Addis Ababa. The findings suggest that interventions should focus on high-risk groups, such as young drivers and those operating automobiles and lorries, particularly during peak traffic hours on Fridays. Educational campaigns should address the most common causes of accidents, including maintaining safe distances and lane discipline. Moreover, improvements to road infrastructure, particularly on asphalt roads, could further enhance road safety.

# Recommendations
- **Targeted Road Safety Campaigns:** Develop educational programs focusing on young drivers, emphasizing safe driving practices.
- **Enhanced Traffic Enforcement:** Increase monitoring and enforcement of traffic laws, particularly on Fridays and during evening rush hours.
- **Infrastructure Improvements:** Prioritize the maintenance and enhancement of asphalt roads, the most common accident sites.
- **Driver Education:** Expand road safety education at the junior high school level to reduce accident involvement among this demographic.
