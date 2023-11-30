# Patterns in Global Happiness

The World Happiness Report, a publication by the Sustainable Development Solutions Network, draws its insights from Gallup World Poll data. This report mirrors the global plea for greater emphasis on the global call for prioritizing happiness and well-being in governmental policy considerations. It assesses the current global happiness levels and delves into how the study of happiness clarifies the differences in happiness among individuals and nations, emphasizing its significance in policymaking.

The annual happiness rankings are rooted in life evaluations conducted through the Gallup World Poll. These rankings stem from responses to the principal life evaluation question, utilizing the Cantril ladder. This approach prompts individuals to visualize a scale where 10 signifies the highest possible life satisfaction and 0 signifies the lowest. Respondents are then prompted to assess their own current lives on this scale.

This analysis draws on data from the World Happiness Report and is divided into two sections: one examining the current year of 2023, and the other providing an in-depth assessment across all recorded years.

*Relveant questuons include:*
+ What country-specific features are most commonly associated with higher levels of happiness?
+ Does a general upward trend in happiness exist? Is happiness globally correlated, or does it predominantly manifest at an individual country level?
+ Can a nation experiencing unhappiness anticipate a progression towards greater happiness over time?

</details>

<details>

<summary>Happiness in 2023s</summary>

### 2023
A happiness score surpassing 6 signifies a state of happiness, while a score below 4.5 indicates unhappiness, with scores falling in-between being categorized as moderate.

<img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/happiness_scale.png">

Visual 1 illustrates that in 2023, the majority of countries reported a state of happiness or moderate happiness, 55 and 54 respectively. Conversely, a minority, comprising of 28 countries, reported an unhappy state. Overall, the global trend for 2023 indicates a prevalence of moderate to higher happiness levels. Visual 2 illustrates that the majority of countries had a happiness score ranging between 5 and 6 in 2023.

<table>
<tr><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_16.png" width="390" height="370"> </th><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_03.png"  width="411" height="370"></th></tr>
<tr><td>
   
*Visual 1; Number of countries by signal in 2023*
</td><td>
   
*Visual 2; Distriutiuon of happiness scores by number of countries in 2023* 
</td></tr> 
</table>

<p>&nbsp;</p>

Visual 3 exhibits the countries boasting the highest and lowest happiness scores in 2023. The disparity between these two groups is substantial, with the highest scores exceeding double the lowest scores in the most extreme instance. Notably, the nations attaining the highest happiness scores are predominantly located in the European region, whereas those registering the lowest scores are primarily situated in the African region.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_02.png"  width="700" height="500"> | 
|:--:| 
| *Visual 3; Countries witht he highest and lowest happiness scores in 2023* | 

<p>&nbsp;</p>

Visual 4 depicts North America as having the highest average happiness score, while Africa demonstrates the lowest average happiness score. Remarkably, regions with lower average happiness scores, compared to other regions, exhibit greater variability among individual countries. For instance, the Middle East stands out with the highest variety, showcasing countries with both low and high happiness scores.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_04.png"  width="600" height="450"> | 
|:--:| 
| *Visual 4; Happiness scores by region in 2023* | 

<p>&nbsp;</p>

Visuals 5 and 6 present the distribution of countries based on their happiness scores. Despite North America showing a high average happiness score, it doesn't comprise the largest number of countries. Europe and Africa stand out in these visuals due to their higher representatioN. Europe hosts the most countries with higher happiness scores, while Africa contains the most countries with lower happiness scores.

<table>
<tr><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_05.png"  width="570" height="380"> </th><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_06.png"  width="570" height="380"></th></tr>
<tr><td>
   
*Visual 5; Distribution of happiness scores by region in 2023*
</td><td>
   
*Visual 6; Country feature correlations in 2023*
</td></tr> 
</table>

<p>&nbsp;</p>

Visual 7 utilizes a heatmap to demonstrate correlations among country features in 2023. Darker shades of blue indicate stronger correlations, while lighter shades imply weaker correlations. Notably, variables intersecting with the Happiness score, GDP, Social support, Life expectancy, and Freedom, exhibit significantly darker shades of blue on the heatmap. This suggests a strong positive correlation among these factors, indicating they are likely to increase together. Generosity appears closer to 0, suggesting it may not have a substantial impact on other country features. Conversely, Perception of corruption is depicted as negatively correlated, supporting the notion that reduced corruption tends to correlate with higher happiness.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_07.png"  width="700" height="580"> | 
|:--:| 
| *Visual 7; Country feature correlation heatmap in 2023* | 

<p>&nbsp;</p>

Visual 9 compiles all positive correlations, suggesting that the cluster of country features are likely strongly associated with each other. In Visual 8, correlations to happiness are ranked from highest to lowest. Notably, Social support exhibits the highest correlation by a considerable margin, standing at 0.83, followed by GDP at 0.78 and Life expectancy at 0.73. Although still significant, Freedom shows the least correlation among the strongly associated group at 0.66. Perception of corruption is negatively correlated but not significantly so, lying below -0.50 at -0.47.

<table>
<tr><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_17.png"  width="300" height="200"> </th><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_18.png"  width="340" height="240"></th></tr>
<tr><td>
   
*Visual 8; Country featrues correlated to happiness in 2023*
</td><td>
   
*Visual 9; Country featrues with a positive correlation in 2023*
</td></tr> 
</table>

<p>&nbsp;</p>

Visuals 10 through 15 all depict scatterplots of country features correlated to happiness plotted by country in 2023 in a descending order. The line of best fit is included and illustrates correlation. Social support, GDP, Life expectancy, and Freedom all show positive slopes on their line of best fit, indicating a positive correlation to the Happiness score. Social support has the steepest positive slope. Generosity is shown to have a very horizontal slope comparatively, supporting a lack of correlation to Happiness. Perception of corruption is the only country feature depicting a negative slope, supporting a negative correlation. The scatterplot also depicts that Europe and Africa dominate world happiness, followed by Asia and Latin America.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_08.png"  width="595" height="493"> | 
|:--:| 
| *Visual 10; Happiness score and Social support plotted by country in 2023, <br> illustrating a siginificant positive correaltion of 0.83* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_09.png"  width="595" height="493"> | 
|:--:| 
| *Visual 11; Happiness score and GDP plotted by country in 2023, <br> illustrating a positive siginificant correaltion of 0.78* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_10.png"  width="595" height="493"> | 
|:--:| 
| *Visual 12; Happiness score and Life expectancy plotted by country in 2023, <br> illustrating a siginificant positive correaltion of 0.73* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_11.png"  width="595" height="493"> | 
|:--:| 
| *Visual 13; Happiness score and Freedom plotted by country in 2023, <br> illustrating a positive siginificant correaltion of 0.66* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_12.png"  width="595" height="493"> | 
|:--:| 
| *Visual 14; Happiness score and Generosity plotted by country in 2023, <br> illustrating a lack of correlation at 0.05.* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_13.png"  width="595" height="493"> | 
|:--:| 
| *Visual 15; Happiness score and Perception of corruption plotted by country in 2023, <br> illustrating a negative correaltion of -0.47* | 

</details>

</details>

<details>

<summary>Happiness in All Recorded Years</summary>

### All Available years

The World Happiness Report covers data from 2005 to 2023, encompassing a total of 18 years. Visual 16 showcases the frequency of reports over time, with each report representing an individual country. The number of reports saw a gradual increase from 2006, reaching an average of 142.33 reports between 2011 and 2019. However, a substantial drop occurred during 2020, 2021, and 2022, followed by a resurgence of reports in 2023. This decline is possibly attributed to countries focusing on global instability during the COVID-19 pandemic, gradually resuming report submissions in 2023.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_01.png"  width="595" height="493"> | 
|:--:| 
| *Visual 15; Happiness score and Perception of corruption plotted by country in 2023, <br> illustrating a negative correaltion of -0.47* | 

<p>&nbsp;</p>

A total of 165 countries are represented across the 18-year period. In Visual 17, the number of reports by the number of countries is detailed. The visualization indicates that the majority of countries have consistently reported every year for the entire span of 18 years, with most nations contributing data for at least 15 years.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_02.png" width="250" height="500"> | 
|:--:| 
| *Visual 15; Happiness score and Perception of corruption plotted by country in 2023, <br> illustrating a negative correaltion of -0.47* | 

<p>&nbsp;</p>

</details>













</details>

<details>

<summary>Conclusions</summary>

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_05.png"  width="570" height="380"> | 
|:--:| 
| *Visual 5; Distribution of happiness scores by region* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_06.png"  width="570" height="380"> | 
|:--:| 
| *Visual 6; Distribution of happiness scores by region* | 


| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_16.png" width="350" height="370"> | 
|:--:| 
| *Image 1* | 


</details>
