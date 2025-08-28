# Machine Learning Olympiad-2024: CO2 Emissions Prediction Challenge



## Problem Description:

The dataset, prepared from the World Bank DataBank, provided for the "CO2 Emissions Prediction Challenge" encompasses a diverse array of indicators spanning socio-economic and environmental domains, crucial for predicting CO2 emissions per capita and understanding their environmental impact. Indicators such as access to electricity, agricultural land, annual freshwater withdrawals, arable land, forest area, electric power consumption, energy use, renewable energy output, population growth, and GDP per capita serve as key predictors in this context.

Each indicator offers valuable insights into the socio-economic and environmental factors influencing CO2 emissions. For instance, access to electricity and energy consumption metrics reflect the level of industrialization and development in a country, directly impacting CO2 emissions. Similarly, agricultural land, arable land, and forest area metrics provide insights into land use patterns and deforestation rates, which significantly contribute to CO2 emissions and environmental degradation.

The importance of addressing CO2 emissions lies in their detrimental impact on climate change, air quality, and global sustainability. Rising CO2 emissions exacerbate global warming, leading to adverse effects such as extreme weather events, sea-level rise, and biodiversity loss. By accurately predicting future CO2 emissions, this competition aims to raise awareness of the urgency to mitigate climate change and inspire innovative solutions to curb emissions. Through data-driven insights and predictive modeling, participants can contribute to informing policymakers, businesses, and communities about the imperative need for sustainable development practices and emission reduction strategies. This competition serves as a catalyst for fostering collaboration and driving meaningful action towards a more sustainable and resilient future.

In case you need any support, join our Facebook group: https://facebook.com/groups/tfug.nb

Evaluation
Submissions will be scored based on the Root Mean Squared Error (RMSE) between the predicted and actual CO2 emissions per capita for each country for the year 2016-2020 and 2030. The RMSE is calculated as follows:

where:

n is the number of countries in the test set,
yi​ is the actual CO2 emissions per capita for country i, and
y^​i​ is the predicted CO2 emissions per capita for country i.

The team with the lowest RMSE will be ranked highest on the leaderboard. In the event of a tie, the team that submitted their solution first will be ranked higher.

Submission File
For each country in the test set, you must predict the CO2 emissions per capita for the year 2030. You will make predictions for the year 2030 using your models trained on 2000-2015 data. Your submission file will contain predicted values for the year 2016-2020 (for validation) and 2030. The file should contain a header and have the following format:

Country Name,2016 [YR2016],2017 [YR2017],2018 [YR2018],2019 [YR2019],2020 [YR2020],2030 [YR2030]

Afghanistan,0,0,0,0,0,0
Albania,0,0,0,0,0,0
Algeria,0,0,0,0,0,0
...
In this format:

Country Name are the unique identifiers for each country.
2016 [YR2016] - 2020 [YR2020], 2030 [YR2030] are the predicted CO2 emissions per capita for the year 2016-2020 and 2030.
Your submission should have predictions for all countries in the test set. The submission file should be in CSV format.
