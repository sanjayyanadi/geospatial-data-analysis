# geospatial-data-analysis

## Context
Over the years the earthquakes have been recorded by different organisations in Turkey. Bogazici University, as the most successful university in Turkey, has a earthquake research center and they collected up all the data during the years. They have the most technological devices to uncover the specifications about the earthquakes. The data was collected from the database with particular filters.

## Content
The data covers up all the recorded earthquakes in the latitudes between 25 - 50; longitudes 15 - 60. As the metering stations are placed in Turkey most of the recorded earthquakes are in latitudes between 35 - 45; longitudes 25 - 45. The database search time filter was set to dates 27/09/1910 to 27/09/2017. As there are too many earthquakes which have intensities smaller than 4.0, the filter of intensity was set to 3.5 to 9.0 (there was no earthquakes recorded larger than 9.0 intensity). Not being an earthquake specilist or geologist, I have no idea about the different kind of intensity measurements in the dataset (the columns between xM and Ms).

## Acknowledgements
All the data here is owned by "Boğaziçi Üniversitesi Rektörlüğü" and it can only be used for uncommercial issues with regards to "Boğaziçi Üniversitesi Kandilli Rasathanesi ve Deprem Araştırma Enstitüsü Bölgesel Deprem-Tsunami İzleme ve Değerlendirme Merkezi".

## Inspiration
I hope all kind of data scientists would be interested in this data in order to: - Visualize the current data on any kind of GIS. - Reveal some truths and correleations behind and across the data. - Analyze seasonality across months, years and decades. - Improve any kind of data model which can be useful to represent the eathquakes in Turkey. - Develop algorithms to predict the earthquake with an intensity, an interval and a coordinate corridor.

## FEATURES
* MD
* ML
* Mw
* Ms
* Mb
Biggest magnitude value in specified magnitude values (MD, ML, Mw, Ms and Mb)
Magnitude types
(MD: Duration, ML: Local, Mw: Moment, Ms: Surface wave, Mb: Body-wave)

The larger circles represent higher magnitude (xM) values. The different colors indicate the different depths

0.0 (zero) means no calculation for that type of magnitude


## WHAT IS RICHTER SCALE
The Richter magnitude scale was developed in 1935 by Charles F. Richter of the California Institute of Technology as a mathematical device to compare the size of earthquakes. The magnitude of an earthquake is determined from the logarithm of the amplitude of waves recorded by seismographs.

The Richter scale has its limitations, as it does not reflect the impact of vertical movement, which can be the wave movement causing the greatest amount of damage. However, for most earthquakes the Richter scale has provided reasonably well correlation with the resulting damage.

## CREATING NEW FEATURES
RICHTER
1.0–1.9 Micro I
Microearthquakes, not felt, or felt rarely. Recorded by seismographs.Continual/several million per year

2.0–2.9 Minor I to II
Felt slightly by some people. No damage to buildings. Over one million per year

3.0–3.9 Minor III to IV
Often felt by people, but very rarely causes damage. Shaking of indoor objects can be noticeable. Over 100,000 per year

4.0–4.9 Light IV to VI
Noticeable shaking of indoor objects and rattling noises. Felt by most people in the affected area. Slightly felt outside. Generally causes zero to minimal damage. Moderate to significant damage very unlikely. Some objects may fall off shelves or be knocked over. 10,000 to 15,000 per year

5.0–5.9 Moderate VI to VII
Can cause damage of varying severity to poorly constructed buildings. Zero to slight damage to all other buildings. Felt by everyone. 1,000 to 1,500 per year

6.0–6.9 Strong VIII to X
Damage to a moderate number of well-built structures in populated areas. Earthquake-resistant structures survive with slight to moderate damage. Poorly designed structures receive moderate to severe damage. Felt in wider areas; up to hundreds of miles/kilometers from the epicenter. Strong to violent shaking in epicentral area. 100 to 150 per year

7.0–7.9 Major X or greater
Causes damage to most buildings, some to partially or completely collapse or receive severe damage. Well-designed structures are likely to receive damage. Felt across great distances with major damage mostly limited to 250 km from epicenter. 10 to 20 per year

8.0–8.9 Great
Major damage to buildings, structures likely to be destroyed. Will cause moderate to heavy damage to sturdy or earthquake-resistant buildings. Damaging in large areas. Felt in extremely large regions. One per year

9.0 and Greater
At or near total destruction – severe damage or collapse to all buildings. Heavy damage and shaking extends to distant locations. Permanent changes in ground topography. One per 10 to 50 years.

# CONCLUSION:
For the dataset of the earthquake in Turkey. For this project, we did feature engineering, exploratory data analysis, and geospatial data analysis. and analysed the patterns and distribution with respect to duration, locality, moment, surface wave, and body wave towards time.

And using an unsupervised model, KMeans, we clustered the data with respect to the k value. For this model using the elbow method, we get a k value of 4 and cluster the data into four centroid groups.



