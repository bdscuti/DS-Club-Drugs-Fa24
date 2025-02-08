# team-DRUG-fa24
This is our Data Dive Project with the Data Science Club at UIUC. We analyzed the Cook County's death data from the Medical Examiner's Office https://www.cookcountyil.gov/agency/medical-examiners-office. We focused on the 14,803 drug-related deaths out of the 85,049 total overall deaths. The dataset contains 30 different features, which we analyzed for notable trends. Fentanyl and heroin alone deaths accounted for the majority of drug overdose deaths, while cold exposure was the most significant secondary cause. We hot encoded the manner of death column with drug overdose representing a 1, and we used a logistic regression model to predict the binary manner of death from all the 29 other features in the data set. We found that females were negatively correlated with a drug overdose death, while white or Latino and male features found positive correlations.

It was interesting to note that accidental deaths were most common amongst 45 to 50-year-olds, while suicide was typically the most common amongst 35 to 40-year-olds. Drug overdose accidents happen most typically in the mornings. Drug overdose incidents had a spike in the years 2020, 2021, and 2022. Commissioner District 2 had 110 deaths, District 1: 86 deaths, District 3: had 46 deaths, and 7: 42 deaths.

I used GeoJson data of the zip code borders in Illinois and a dataset of the median income level by zip code to create a Folium Choropleth map of the proportion of people in poverty. An annual income of $25,000 was considered as the threshold for poverty. Furthermore, a MarkerCluster object was also added to the map to depict the overdose counts against the poverty levels. We found that zip codes 60624 (in West Garfield Park), 60612 (in East Garfield Park),  60623 (split between North and South Lawndale), and 60651 (in Humboldt Park) had the most drug overdoses. zip_proportion_poverty depicts this breakdown by zip code and the percentage of poverty sorted from high to low. Unfortunately, we do not have the poverty level for these zip codes. The highest proportion of impoverishment is 0.59. 


![image](https://github.com/user-attachments/assets/a9e5efce-1e2f-4c58-adb6-1b5d90d26904)
![image](https://github.com/user-attachments/assets/6c84b7ef-38d2-4aef-b0a7-5739e5080e56)
![image](https://github.com/user-attachments/assets/b4a0c191-53a2-4e81-8a65-70e7f35b44c4)
![image](https://github.com/user-attachments/assets/8db6607f-a971-4729-9b58-47ff45ea4753)




