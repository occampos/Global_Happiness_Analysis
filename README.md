# Patterns in Global Happiness

The World Happiness Report, a publication by the Sustainable Development Solutions Network, draws its insights from Gallup World Poll data. This report mirrors the global plea for greater emphasis on the global call for prioritizing happiness and well-being in governmental policy considerations. It assesses the current global happiness levels and delves into how the study of happiness clarifies the differences in happiness among individuals and nations, emphasizing its significance in policymaking.

The annual happiness rankings are rooted in life evaluations conducted through the Gallup World Poll. These rankings stem from responses to the principal life evaluation question, utilizing the Cantril ladder. This approach prompts individuals to visualize a scale where 10 signifies the highest possible life satisfaction and 0 signifies the lowest. Respondents are then prompted to assess their own current lives on this scale.

This analysis draws on data from the World Happiness Report and is divided into two sections: one examining the current year of 2023, and the other providing an assessment across all recorded years.

*Relveant questuons include:*
+ What country-specific features are most commonly associated with higher levels of happiness?
+ Does a general upward trend in happiness exist?
+ Do nations experiencing an above average happiness likely to mantain its happiness?
+ Is happiness globally correlated, or does it predominantly manifest at an individual country level?
+ Can a nation experiencing unhappiness anticipate a progression towards greater happiness over time?
+ Has the pandemic in 2020 impacted the world consistenly?
  
</details>

<details>

<summary>Happiness in 2023</summary>

### 2023
A happiness score surpassing 6 signifies a state of happiness, while a score below 4.5 indicates unhappiness, with scores falling in-between being categorized as moderate.

<img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/happiness_scale.png">

The majority of countries reported a state of happiness or moderate happiness, as shown in Visual 1 as 55 and 54 respectively. Conversely, a minority, comprising of 28 countries, reported an unhappy state. Overall, the global trend for 2023 indicates a prevalence of moderate to higher happiness levels. Visual 2 illustrates that the majority of countries had a happiness score ranging between 5 and 6 in 2023.

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

Visual 7 utilizes a heatmap to demonstrate correlations among country features in 2023. Darker shades of blue indicate stronger positive correlations, darker shades of red imply stronger negative correlations and whiter shades imply weaker correlations. Notably, variables intersecting with the Happiness score, GDP, Social support, Life expectancy, and Freedom, exhibit significantly darker shades of blue on the heatmap. This suggests a strong positive correlation among these factors, indicating they are likely to increase together. Generosity appears closer to 0, suggesting it may not have a substantial impact on other country features. Conversely, Perception of corruption is depicted as negatively correlated, supporting the notion that reduced corruption tends to correlate with higher happiness.

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

Visuals 10 through 15 all depict scatterplots of country features correlated to happiness by region in 2023 in descending order. The line of best fit is included to better illustrate correlation. Correlation is shown by how well data points fit along the line of best fit. Social support, GDP, life expectancy, and freedom all show data points that are plotted along the line of best fit pretty well, indicating a positive correlation to the happiness score. Social support fits the tightest, while freedom is the most loose positivdly correlation, which is shown by their correlation coefficients of 0.83 and 0.66 respectively. Generosity is shown to have very loose fitting data points, supporting a lack of correlation to happiness. Perception of corruption is the only country feature depicting a negative slope, while still falling well along the line of best fit, supporting a negative correlation. The scatterplot also depicts that Europe and Africa dominate world happiness, followed by Asia and Latin America. This is due to the number of countries in each region.

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
| *Visual 14; Happiness score and Generosity plotted by country in 2023, <br> illustrating a lack of correlation at 0.04* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_2023/data_2023_13.png"  width="595" height="493"> | 
|:--:| 
| *Visual 15; Happiness score and Perception of Corruption plotted by country in 2023, <br> illustrating a negative correaltion of -0.47* | 

</details>

</details>

<details>

<summary>Happiness in All Recorded Years</summary>





### All Recorded years

The World Happiness Report covers data from 2005 to 2023, encompassing a total of 18 years. Visual 16 showcases the frequency of reports over time, with each report representing an individual country. The number of reports saw a gradual increase from 2006, reaching an average of 142.33 reports between 2011 and 2019. However, a substantial drop occurred during 2020, 2021, and 2022, followed by a resurgence of reports in 2023. This decline is possibly attributed to countries focusing on global instability during the COVID-19 pandemic, gradually resuming report submissions in 2023.

| <img src="https://github.com/occampos/Patterns_In_Happiness/blob/main/Visuals/data_all_years/data_all_years_01.png"  width="700" height="550"> | 
|:--:| 
| *Visual 16; Countries reported over time* | 

<p>&nbsp;</p>

A total of 165 countries are represented across the 18-year period. In Visual 17 and 18, the number of reports by the number of countries is detailed. The visualization indicates that the majority of countries have consistently reported every year for the entire span of 18 years, with most nations contributing data for at least 15 years.

<table>
<tr><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_03.png" width="595" height="493"> </th><th><img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_02.png" width="200" height="500"> </th></tr>
<tr><td>
   
*Visual 17; Number of reports by the number of countries*
</td><td>
   
*Visual 18; Table of number of reports by the number of countries*
</td></tr> 
</table>

<p>&nbsp;</p>

Visual 19 shows that until 2019, there had been a general upward trend in the overall happiness of recorded countries worldwide. However, the onset of the COVID pandemic in the year 2020 can be said to have significantly impacted global happiness levels, leading to a notable decline in global happiness. According to the data provided, an indiciation on a rebound in happines after the decline has yet to be observed. 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_04.png" width="800" height="600"> | 
|:--:| 
| *Visual 19; Global happiness over time* | 

<p>&nbsp;</p>

The global trend of happiness differs greatly from regional trends. Visual 20 highlights this difference by plotting happiness over time by region. North America contains the fewest countries but maintains the highest average happiness score, while Africa retained the lowest average happiness score. Interestingly, in 2020, certain regions reacted differently to the COVID pandemic compared to the global trend, which experienced a significant decline in happiness scores. Europe had an insignificant shift in happiness during this time, while Latin/South America actually had an increase. In 2020, Latin/South America experienced an increase in average happiness scores despite other regions experiencing a stark decline.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_05.png" width="800" height="600"> | 
|:--:| 
| *Visual 20; Happiness over time by region* | 

<p>&nbsp;</p>

The country feature correlation matrix for all recorded years, depicted by Visual 21, looks very similar to the correlation matrix in 2023. The same country features (GDP, social support, life expectancy and freedom) are shown to be correlated with happiness. Similarly to 2023, generosity has a slight correlation, while perception of corruption has a notable negative correlation. However by plotting each country feature against happiness additional insights and trends are observed.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_06.png" width="700" height="580"> | 
|:--:| 
| *Visual 21; Country feature correlation heatmap in all recorded years* | 

<p>&nbsp;</p>

Visuals 22 through 26 are scatterplots of country features correlated to happiness by region for all recorded years in descending order. Similarly to 2023, social support, GDP, life expectancy, and freedom all indicate a positive correlation to the happiness score. However, GDP has surpassed social support as the most correlated with coefficients at 0.78 and 0.73 respectively. GDP's data points fit the line of best fit the tightest, hence a higher correlation. Generosity is shown to have a very loose fit, supporting a lack of correlation to happiness, and Perception of Corruption shows a negative correlation.

| <img src="https://github.com/occampos/Patterns_In_Happiness/blob/main/Visuals/data_all_years/data_all_years_08.png" width="700" height="600"> | 
|:--:| 
| *Visual 22; Happiness score and GDP plotted by country for all recorded years, <br> illustrating a positive siginificant correaltion of 0.78* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_07.png" width="700" height="600"> | 
|:--:| 
| *Visual 23; Happiness score and Social support plotted by country for all recorded years, <br> illustrating a siginificant positive correaltion of 0.73* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_09.png" width="700" height="600"> | 
|:--:| 
| *Visual 24; Happiness score and Life expectancy plotted by country for all recorded years, <br> illustrating a siginificant positive correaltion of 0.68* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_10.png" width="700" height="600"> | 
|:--:| 
| *Visual 24; Happiness score and Freedom plotted by country for all recorded years, <br> illustrating a positive siginificant correaltion of 0.54* | 

<p>&nbsp;</p>

Interestingly, a distinct U shaped pattern can be seen in the plot for Generosity against Happiness Score. This supports that Generosity has less value to happiness when happiness is growing or at an average and more value to happiness when happiness is at it's or at it's highest.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_11.png" width="700" height="600"> | 
|:--:| 
| *Visual 25*; Happiness score and Generosity plotted by country for all recorded years, <br> illustrating a lack of correlation at 0.17 | 

<p>&nbsp;</p>

Additionally, a steep drop-off of Perception of Corruption is observed after around a Happiness Score of 6.5. This supports that for a country to have the greatest likelihood of achieving the highest happiness levels, the country's Perception of Corruption should fall. However, this also shows that Perception of Corruption isn't valued as much comparatively until a certain level of happiness is achieved.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_12.png" width="700" height="600"> | 
|:--:| 
| *Visual 26; Happiness score and Perception of Corruption plotted by country for all recorded years, <br> illustrating a negative correaltion of -0.43* | 

<p>&nbsp;</p>

Variance describes the spread of a set of values in a dataset. It quantifies how far numbers in a dataset are from the mean and provides insight into the degree to which data points differ from one another. To help understand what drives an increase in happiness in a country, I divided the nations into two groups: those with the highest variance (indicating unstable happiness) and those with the lowest variance (indicating stable happiness). Visual 27 compares the Happiness Score of those groups with the global average over time. It can be seen that countries with the most variance have a higher average happiness than both the global average and countries with the least variance. This supports that as a country reaches a certain level of happiness it is likely to maintain that happiness.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_13.png" width="800" height="600"> | 
|:--:| 
| *Visual 27; Average happiness in countries with highest variance and lowest variance* | 

<p>&nbsp;</p>

Visual 28 and 29 illustrate correlations between features for the highest variance and lowest variance countries through heatmaps. Happiness Score, GDP, Social Support, and Life Expectancy remain positively correlated to one another in both of the two groups, albeit the lowest variance countries have a noticeably weaker correlation in general. <br> 
Notably, Generosity is negatively correlated to GDP and Social Support when variance is high, while there is little correlation when variance is low. This hints that Generosity is impactful only when countries are experiencing instability in happiness. Freedom shifts from being positively correlated to most features in low variation countries to a much weaker correlation in high variance countries. This supports that Freedom plays a less impactful role in happiness when countries have variable happiness. Similarly, Perception of Corruption also experiences a shift from strong correlation (negative) to a much weaker correlation in countries with variable happiness.

| <img src="https://github.com/occampos/Patterns_In_Happiness/blob/main/Visuals/data_all_years/data_all_years_14.png" width="700" height="580"> | 
|:--:| 
| *Visual 28; Country feature correlation heatmap for countries with lowest varaince in happiness* | 

| <img src="https://github.com/occampos/Patterns_In_Happiness/blob/main/Visuals/data_all_years/data_all_years_15.png" width="700" height="580"> | 
|:--:| 
| *Visual 29; Country feature correlation heatmap for countries with highest varaince in happiness* | 

<p>&nbsp;</p>

Visual 30 higlights the difference between correlation in happiness between the two groups. Interestingly, Perception of Corruption has the greatest difference in correlation at a change of 0.58. This supports the idea that corruption has a smaller impact on happiness in countries that do not have stable happiness, and once a country reaches a certain level of happiness and thus less problems are immediately present, then corruption has a larger effect on happiness. The same can be said for Freedom and GDP, to a less significant extent, at differences of 0.35 and 0.26 respectively. Social Support, Generosity, and Life Expectancy show insignificant differences in correlation between the two groups. <br>
Visuals 28, 29, and 30 suggest that in countries where variance in happiness is high, and thus a combination of problems exists, Freedom and Corruption are not prioritized, while Generosity is immediately noticed. In contrast, in countries where variance in happiness is low and fewer problems are present in every day life, Generosity has less of a noticeable impact, and attention can be focused on Freedom and Corruption on a larger scale.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_16.png" width="546" height="215"> | 
|:--:| 
| *Visual 30; Country feature correlation heatmap for countries with highest varaince in happiness* | 

<p>&nbsp;</p>

Can a country's happiness be traced to wider global happiness trends, or does it predominantly hinge on the unique circumstances within that country? Visual 31 illustrates the Happiness Score over time for individual countries (black) contrasted with the global average (yellow). Initially, there seem to be no discernible patterns, giving the appearance of a disorganized jumble. Based on this visual, one might assume that a country's happiness is disconnected from the global average.

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_18.png" width="800" height="600">> | 
|:--:| 
| *Visual 31; Happiness over time by country compared to the global average shown in yellow* | 

<p>&nbsp;</p>

beans
The correlation to  33 is a table describing the correlation to the global average by country while visual 34 illustrates it on a scatterplot. On average, individual countries are slightly positively correlated to the global average at () but are more shown to be influenced by local circumstances. Notably, no region has a discernable pattern despite having significant differencees in average happiness, supporting that a single country's happiness isnt primarily driven by global shifts. 

INSERT .DESCRIBE()  & INSERT TOP/BOTTOM Correlated countries

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_21.png" width="248" height="238"> | 
|:--:| 
| *Visual 32; Individual country happiness correlation to global average happiness* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_19.png" width="847" height="600"> | 
|:--:| 
| *Visual 33; Individual country happiness correlation to global average happiness* | 

| <img src="https://raw.githubusercontent.com/occampos/Patterns_In_Happiness/main/Visuals/data_all_years/data_all_years_20.png" width="847" height="600"> | 
|:--:| 
| *Visual 34; Individual country happiness correlation to global average happiness* | 

Can a nation experiencing unhappiness anticipate a progression towards greater happiness over time? This questoin can be studied by focusing on patterns arising after a certain amount of consecutive years. Is an outcome for common after just two years? or is there a prevelent pattern after 15 years?















</details>













</details>

<details>

<summary>Conclusions</summary>

BEANS

</details>
