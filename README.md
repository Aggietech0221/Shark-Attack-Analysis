# Shark-Attack-Analysis

![](SSSHA.png)

##Introduction

Over the years, there has been numbers of shark attack on humans, both provoked and unprovoked cases in different countries especially U.S has been documented. According to the international shark attack report, the exact figure for the past 100 years is unknown but a significant number of shark attack has been reported in the U.S. This report analyses insights drawn from both provoked and unprovoked cases of shark attacks on humans in 133 different countries in 193 years.

##Data Overview

The dataset is a raw and messy data with 22 columns and 6096 rows containing multiple blank rows, empty cells, duplicate values and missing data with incorrect datatypes.

##Problem Statement

As at current, the exact figure, areas and locations of attacks are still unknown, knowing the dangerous areas that are more prone to shark attacks will aid in mitigating the risk and the reason why analysis is needed to be done on areas where attacks has been reported.

##Key Metrics

-Total shark attacks

-Total number of years

-Total number of countries reported

##Skills Demonstrated

-Data Gathering/collection: The dataset was retrieved from a Global shark attack file

-Data Cleaning and Transformation: Using power query in power Bi, Blank rows and duplicates were removed, the date and time column was transformed using DAX expression, missing values in the Age and date columns were filled with the average figures, the country, areas and name columns were trim and formatted to give a clear and error free analysis

-Quick measure: This was use to generate quick analysis such as the key metrics

-Dashboard Automation

-Data modelling: One to many relationships was created with the calendar table created with DAX expression in power Bi

-Data Visualization: A graphical representation of analysis done and insights drawn was created to fit into a page which communicate perfectly the areas and locations prone to more danger, shark species involve in attacks and injury from attacks

##Visualization

![](SHA.png)

##Analysis (Insight)

-What is the trend seen from number of shark attacks annually over time since 1900:

Based on the chart, the trend is non-linear which is characterised with an exponential growth in the middle and a sudden drop at the end, this can be as a result of low intervention or increased report and awareness and the drop in recent years as a result of high intervention to mitigate the problem.

-Which country report the most shark attacks, within those countries, which area and locations seems to be more dangerous: U.S.A., Australia and South Africa are countries with the most reported attacks having 1969, 1176 and 506 shark attacks respectively in 193 years.

In U.S.A., Florida (943 reported shark attacks), California (268 reported shark attacks) and Hawaii (256 reported shark attacks) are the most dangerous areas while the most dangerous locations are New Smyrna beach (162 reported shark attacks) and Daytona beach (33 reported shark attacks) in Volusia county. 

In Australia, New south wales (438 attacks), Queensland (287 attacks) and Western Australia (163 attack) are the most dangerous areas and the most dangerous locations are Near Thursday island (9 reported shark attack) and Newcastle (8 reported shark attacks). 

In South Africa, Kwazulu (188 attacks), Western cape province (171 attacks) and Eastern cape province (141 attacks) are the most dangerous areas with Durban, Nahoon and Mossel Bay as the most dangerous location in Dubai with 10 reported shark attacks each.

-What body parts are most often injured:

The most injured part is the foot, this shows most victims were surfers therefore, the need for water surfers to always be alert and keep their foot protected.

-Are shark attack more common at a particular time of the day: 

Shark attack are most common at Noon around 3:00pm and 12:00pm, this indicate that though, sharks can nocturnal some are still active during the day probably due to activities within the water surface that can attract their attention.

-What species of sharks are attacking most often: Species of White sharks, Tiger sharks and Bull sharks attacks more often.

##Conclusion and Recommendation

Report of shark attack on humans has reduced in the recent years compare to the previous years which indicates intervention and reduction in injuries or death from reported shark attacks. Nevertheless, majority of attacked areas are still unknown, I will recommend:

-More intervention should be put into place such as hiring more researchers to collect information on attacks 

-Water surefers in dangerous areas should be provided anti-shark booties and just as a wet suit.
