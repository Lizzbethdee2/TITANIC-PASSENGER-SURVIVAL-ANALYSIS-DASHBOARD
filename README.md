# TITANIC-PASSENGER-SURVIVAL-ANALYSIS-DASHBOARD
![Screenshot (108)](https://github.com/user-attachments/assets/878b7d4e-971c-41cc-8bf9-6f94d8fbf3e5)

Titanic Passenger Survival Analysis Dashboard

This dashboard provides a multi-dimensional analysis of Titanic passengers, focusing on survival rates, demographics, and travel-related variables like cabin, embarkation point, and fare.

📊 Key Visuals and Insights
1. Sum of IsAlone by Cabin
Insight: Cabin C85 has the highest number (69) of passengers who were alone, followed by E46, G6, and one other cabin.

Implication: Being alone may be an influencing factor in survival or passenger classification. More investigation can help determine correlation.

2. Count of PassengerId and Sum of Survived
Observation: There were 2966 total passengers, with 1483 survivors.

Survival Rate: ≈ 50% overall survival rate.

Insight: This bar clearly contrasts the total passenger count against the number of survivors, indicating a significant mortality rate.

3. Sum of Survived (Gauge Chart)
Total Survivors: 1483 out of 2966.

Visualization: The gauge offers a fast visual reference of how survival compares to total.

4. Sum of Embarked_C by Cabin
Insight: More passengers from cabins G6, E46, and C85 embarked from location C.

Implication: Embarkation point could be tied to cabin allocation or ticket class. There might be underlying socio-economic data here.

5. Size of Family (Donut Chart)
Sum of Family Size: 11K

Sum of Fare: 164.03K

Insight: The overwhelming majority (≈94%) of the data refers to Fare, while only 6% relates to Family Size.

Interpretation: While large family sizes were present, fares may have had more impact on survival or were more heavily recorded.

6. Sum of Age by Sex
Distribution: Age is almost equally split between male and female.

Insight: This suggests an approximately even distribution of genders in the dataset. Useful for deeper gender-based survival analysis.

7. Sum of Fare
Value: 597.44

Insight: This aggregate value represents the total fare paid by the filtered or total passengers shown.

Note: Interpretation depends on dataset filtering—whether this is average, filtered total, or partial.

📈 Overall Observations & Trends
Balanced Gender & Age Distribution: Males and females are almost equally represented by age sum, which allows for fair gender-based comparison in further analysis.

Survival Rate Close to 50%: This reinforces historical records and is useful for comparing across other dimensions like class, fare, and family.

Cabin Influence: Cabins like C85 had more people traveling alone. Whether this correlates to class or fare paid could be a deeper layer for exploration.

Embarkation Distribution: Embarked_C (likely Cherbourg) had a good number of passengers in high-class cabins—suggesting possible socio-economic relevance.

📌 Recommendations for Deeper Insights
Survival by Gender & Age:

Add a stacked chart or matrix to compare survival rates across gender and age ranges.

Test the "women and children first" theory visually.

Cabin Class vs. Survival:

Analyze how cabin location or type impacted survival rates.

Fare vs. Survival:

Use a scatterplot to show fare paid versus survival status, revealing possible privilege in rescue access.

Family Size Correlation:

Is there a link between larger families and lower/higher survival rates?

Interactive Filtering:

Allow slicing by gender, age group, and embarkation point to improve user-driven exploration.

📘 Conclusion
This dashboard successfully provides a strong overview of the Titanic dataset, emphasizing passenger demographics, cabin data, embarkation details, and survival outcomes. To make it more insightful, focus on comparing survival against categorical variables like gender, cabin, and fare. Adding time-based or route-based factors could provide additional narrative.
