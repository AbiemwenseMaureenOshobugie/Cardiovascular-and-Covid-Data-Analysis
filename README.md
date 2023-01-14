# Cardio-and-Covid-Data-Analysis
Cardio-Covid Analysis

Project: Cardio Analysis
This project aims to provide insights on cardiovascular health by analyzing three datasets: cardio-alco, cardio-base and covid-data. The analysis is intended to answer 13 research questions related to cardiovascular health, alcohol consumption and covid-19.

## Datasets
The cardio-alco dataset contains information on alcohol consumption information for a sample of individuals.
The cardio-base dataset contains information on cardiovascular health and other demographic information for a sample of individuals.
The covid-data dataset contains information on Covid-19 cases and deaths by country.

## Research Questions
Are men more likely to be a smoker than women?
Do people over 50 have higher cholesterol levels than the rest?
How much heavier is the age group with the highest average weight than the age group with the lowest weight?
How tall are the tallest 1% of people?
Look at the cumulative number of confirmed cases in Italy between 2020-02-28 and 2020-03-20. Fit an exponential function (y = Ae^(Bx)) to this set to express cumulative cases as a function of days passed, by minimizing squared loss. What is the difference between the exponential curve and the total number of real cases on 2020-03-20?
When did the difference in total number of confirmed cases between Italy and Germany become more than 10000?
What is the F1 score of the following statement: Countries, where more than 20% of the population is over 65 years old, have death rates over 50 per million inhabitants. Ignore countries, where any of the neccessary information is missing!
What is the probability that a country has GDP over $10000, if we known that they have at least 5 hospital beds per 1000 inhabitants?
What percentage of the population over 50 years old consume alcohol? Ignore those persons, where we have no alcohol consumption information!
What percentage of people are more than 2 standard deviations far from the average height?
Which country has the 3rd highest death rate? Death rate: total number of death per million inhabitants.
Which of the following statements is true with 95% confidence?
Which two features have the highest spearman rank correlation?

## Results
The analysis of the three datasets revealed several findings, including:

Men are 12x more likely to be smokers than women
The highest correlation pair of features are 'ap_hi' and 'ap_lo', with correlation value of 0.74
A probability of 88% that a country has GDP over $10,000, knowing that there are at least 5 hospital beds
The F1 score of Countries where more than 20% of the population is over 65 years old, have death rates over 50 per million inhabitants is  0.73 
The tallest one percent of the people are over 184cm tall
The ratio of the average cholesterol levels for people over 50 is 1.195 compared to the average cholesterol levels for people under 50
There is not a 95% confidence that smokers have higher blood pressure than non-smokers.

## Conclusion
It is important to note that these findings are based on a sample of individuals and may not be representative of the entire population. Further research is needed to confirm these findings and to explore the underlying mechanisms behind the relationships identified in this analysis. Overall, this project highlights the importance of considering multiple factors, such as alcohol consumption, physical activity, and Covid-19, in understanding and addressing health issues.
