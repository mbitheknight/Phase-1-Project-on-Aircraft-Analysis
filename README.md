# Project Title: Aircraft Safety Risk Analysis 

## Project Overview
In this project, I focused on cleaning, analyzing, and visualizing aviation accident data to uncover insights regarding aircraft safety risks. I aimed to provide actionable recommendations for stakeholders as the company expands into purchasing and operating airplanes. This analysis will help identify the aircraft with the lowest operational risks.

## Business Problem
As the company looks to diversify its portfolio by entering the aviation industry, more needs to be known about the risks associated with operating different aircraft. My goal with this project was to analyze historical accident data to offer insights and identify which aircraft present the lowest risk for the company's aviation division.

## The Data
I used a dataset from the National Transportation Safety Board (NTSB), including aviation accident data from 1962 to 2023. This dataset contains information on civil aviation accidents and incidents in the U.S. and international waters. This is the link: https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses

### Data Folder Structure
data/ aviation_accident_data.csv

## Key Points
- I addressed missing values, performed data aggregation, and used visualization techniques to support decision-making.
- The final recommendations are based on actionable insights derived from my dataset analysis.
- The project aims to effectively communicate findings to stakeholders, particularly the head of the aviation division.

## Methodology
1. **Data Cleaning**
   - I handled missing values by identifying and imputing the appropriate data when necessary. I also transformed columns to correct formats, ensuring accurate analysis.

2. **Data Analysis**
   - I conducted exploratory data analysis to calculate key metrics such as accident frequencies and the distribution of injuries by weather condition, engine type, make of the aircraft, and flight purpose.

3. **Data Visualization**
   - I created visualizations using Matplotlib in Jupyter Notebook to present insights into accident trends, accident counts in relation to flight purpose and make, risks associated with different aircraft makes, and the correlation between weather conditions and accident severity.
   - I also did visualizations in Tableau for  accident trends, accident counts in relation to flight purpose and make, and risks associated with different aircraft makes. This is the link: https://public.tableau.com/app/profile/knight.mbithe/viz/AiircraftRiskAnalysisandRecommnendationinteractiveDashboard/RiskAnalysisandRecommendationsInteractiveDashboard?publish=yes

## Recommendations
1. **Recommendation 1**: Based on accident frequency analysis, I recommend avoiding aircraft models with high accident rates (e.g., Cessna).
2. **Recommendation 2**: I suggest prioritizing flight operations under VMC (Visual Meteorological Conditions), as accidents tend to be less severe than those in IMC (Instrument Meteorological Conditions).
3. **Recommendation 3**: I advise considering engine types like Turbo Fan and Turbo Jet, which, despite their higher accident counts, show better safety outcomes regarding survivability and uninjured passengers. Therefore, the high accident counts will be reduced if safety protocols are carefully followed for such engine types.

## Conclusion
In summary, certain aircraft and engine types show better survivability rates despite the high number of accident frequencies and injury severities. Therefore, safety measures need to be implemented to ensure both safety and survivability. My findings will help guide the company in making data-driven decisions about purchasing safer aircraft and mitigating risks in its new aviation venture.

## Contact Information
- **Author**: Knight Mbithe
- **Email**: knightmbithe17@gmail.com

