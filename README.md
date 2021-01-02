# Tableau-Project
Visualization of COVID-19 data from European Center for Disease Control and Prevention (ECDC) 

LINK TO PROJECT

Enclosed is the link to access my Project 4 in Tableau:

https://public.tableau.com/views/Project4_Saibal_Bhattacharya_final/COVID-19Story?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

MOTIVATION 

We are living through a pandemic with no end in sight, and this motivated me to analyze publicly available COVID-19 data in order to learn first hand about global hot spots, compare the US with other countries, and forecast near-term deaths nationwide.      

DATA SOURCE

I obtained the COVID-19 dataset (Excel file) from the website of Our World in Data (Reference 1). Our World in Data hosts data collected and integrated by the European Center for Disease Prevention and Control (ECDC) from across the world. The data is open source, and updated daily. I downloaded the data on Jul 29, 2020, and so my analysis is current as of Jul 28, 2020. Also, the number of cases in this presentation have not been adjusted by the number of cured patients.

TABLEAU STORY - PAGE 1

The 1st page of the story provides a quick look at the distribution of COVID-19 cases and resulting deaths across the globe. 

This map shows the total cases and deaths across all countries in the world. The size of the bubble is proportional to total cases/million while the fill color of the bubble represents the total deaths/million. I have normalized total cases and deaths to million persons to remove the effect of population differences between countries. Thus, this normalization enables me to display the effectiveness of respective governments in tackling this epidemic independent of the size of the country’s population. 

One can zoom-in on different areas of the world map to see through the overlapping bubbles. When the cursor is brought over any bubble, the tooltip box opens showing the total cases and deaths per million in the selected country. This map shows that Qatar has had the highest number of cases per million while San Marino has had the maximum number of deaths per million. The map also displays that some of the Middle Eastern countries like Kuwait, Bahrain, Qatar, and Oman have high number of cases (per million) but with a much lower death rate (per million) than some of the European countries like San Marino, Belgium, UK, and Andorra. The number of cases (per million) in the US are moderately high, and thankfully, the death rate (per million) is lower than the above-mentioned European countries.

TABLEAU STORY - PAGE 2

Here we compare the US with a select group of countries including Brazil, Italy, Germany, India, and South Korea. I selected these countries for different reasons: Brazil - (like the US) has become one of the major epicenters for COVID-19, Italy - was hammered by huge number of cases and deaths earlier than most countries but has managed to gain control over the spread of the virus, Germany - has been a model country that managed to limit the number of cases and deaths, India – with its massive population and limited resources initially recorded limited number of cases which now have grown significantly, but it has had low number of associated deaths, and South Korea - for taking aggressive steps that successfully tamed an initial growth of infections.

PAGE 2 – LEFT CHART

This is a semi-log chart that compares the total cases per million in US and 5 other countries. The total cases (per million) in the US seem to increase exponentially (along a straight line) since Jul 1 with Brazil showing a similar and close profile. The Italian and German success in taming the spread of the virus is clearly seen by near horizontal profiles for these countries. South Korea managed to control the number of cases after an early increase, but a slow increase in the number of cases is observed from May 15 onwards – though the growth rate is far below that of the US or Brazil. Since mid-Jun, the number of cases (per million) has started to grow exponentially in India, though the total number of cases normalized to India’s population indicates far fewer people infected per million in comparison to US and Brazil.

Dr. Anthony Fauci commented (Reference 2) that one of the reasons behind the European success in controlling this virus much better than the US was that the Europeans whole heartedly and in a timely manner shut down their countries, to the extent of 90% of the economy.

PAGE 2 – RIGHT CHART

This chart compares the positivity rate (i.e., number of confirmed cases to number of tests as a percent) prevalent in the US and select other countries. It becomes apparent from the plot that the Italians and the South Koreans have had outstanding success in reducing this positivity rate, especially Italy, which was besieged with very high numbers initially. The US also was able to reduce the positivity rate below 5%, but, unfortunately, since after Jun 15th, the rate has started to creep up to close to 10%. WHO (World Health Organization) recommends (Reference 3) that countries should consider to open up their economies only when the positivity rate has remained at less than 5% for 14 consecutive days. At the time of this writing, only 16 (Reference 3) US states are able to meet WHO’s positivity recommendations. Thus, going forward, it behooves both citizens and government to be aware of this positivity rate in their respective states before caving in to political pressures to open up the economy (perhaps prematurely).

TABLEAU STORY - PAGE 3     

The last page of my story relates to what the current data allows us to forecast about the near future (months) of this evolving COVID-19 epidemic both in the US and globally.  

PAGE 3 – LEFT CHART

This chart shows the forecasted total deaths in the US as of Nov 1 – using Tableau’s forecast tool. Please note that the forecast made by Tableau has no epidemiologic underpinnings, and so is a forecast based on the assumption that no changes in public health policy are implemented in the near future than those present as of the time of this modeling exercise. The model predicts around 235,000 COVID-19 related deaths as of Nov 1, and for comparison, the IHME (Institute of Health Metrics and Evaluation at University of Washington) model predicts around 250,000 deaths by Nov 1. These are very grim numbers, and this kind of data analysis should wake us all up to initiate and implement effective public health policies – there is still time to reduce unnecessary deaths. History will be watching!

Page 3 – RIGHT CHART

The last chart plots a measure of average extreme poverty versus the average per capita GDP of each country in the database. Unfortunately, the database didn’t clearly explain the units used to record extreme poverty. As expected, the plot shows an inverse relationship between poverty and GDP – a power equation describes the trend reasonably well (r2 = 0.69, p-value < 0.0001). The shape of the symbols represents the continents, while the size represents the total number of cases (per million), and the color represents the total deaths (per million). Thus, this plot utilizes multiple marks (shape, size, and color) to display information. 

It becomes apparent from this plot that most of the low GDP countries (such as in Africa and some in Asia) have so far been spared of the wrath of COVID-19 – they have had less cases and fewer deaths. On the other hand, quite against expectations, it is the high GDP European and North American countries that have suffered the most from this epidemic. However, this observation should not be the reason for complacency amongst low GDP countries because this virus is highly contagious and can make its way into less affected countries easily. Thus, low GDP countries need to marshal their limited resources and put in place effective common sense tried-and-tested public health safety measures, and not be influenced by anti-science propaganda (so prevalent over the Internet).   

REFERENCES:

1.  https://ourworldindata.org/coronavirus-source-data
2.  https://www.cnn.com/politics/live-news/fauci-coronavirus-testimony-07-31-20/h_7b051587c9b0584a6f83d07211a8792b
3.  https://coronavirus.jhu.edu/testing/testing-positivity

