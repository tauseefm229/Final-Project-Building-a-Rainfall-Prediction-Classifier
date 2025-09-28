## About The Dataset
The original source of the data is Australian Government's Bureau of Meteorology and the latest data can be gathered from http://www.bom.gov.au/climate/dwo/.

The dataset you'll use in this project was downloaded from Kaggle at https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package/
Column definitions were gathered from http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml

The dataset contains observations of weather metrics for each day from 2008 to 2017, and includes the following fields:

-Field	Description	Unit	Type
-Date	Date of the Observation in YYYY-MM-DD	Date	object
-Location	Location of the Observation	Location	object
-MinTemp	Minimum temperature	Celsius	float
-MaxTemp	Maximum temperature	Celsius	float
-Rainfall	Amount of rainfall	Millimeters	float
-Evaporation	Amount of evaporation	Millimeters	float
-Sunshine	Amount of bright sunshine	hours	float
-WindGustDir	Direction of the strongest gust	Compass Points	object
-WindGustSpeed	Speed of the strongest gust	Kilometers/Hour	object
-WindDir9am	Wind direction averaged over 10 minutes prior to 9am	Compass Points	object
-WindDir3pm	Wind direction averaged over 10 minutes prior to 3pm	Compass Points	object
-WindSpeed9am	Wind speed averaged over 10 minutes prior to 9am	Kilometers/Hour	float
-WndSpeed3pm	Wind speed averaged over 10 minutes prior to 3pm	Kilometers/Hour	float
-Humidity9am	Humidity at 9am	Percent	float
-Humidity3pm	Humidity at 3pm	Percent	float
-Pressure9am	Atmospheric pressure reduced to mean sea level at 9am	Hectopascal	float
-Pressure3pm	Atmospheric pressure reduced to mean sea level at 3pm	Hectopascal	float
-Cloud9am	Fraction of the sky obscured by cloud at 9am	Eights	float
-Cloud3pm	Fraction of the sky obscured by cloud at 3pm	Eights	float
-Temp9am	Temperature at 9am	Celsius	float
-Temp3pm	Temperature at 3pm	Celsius	float
-RainToday	If there was at least 1mm of rain today	Yes/No	object
RainTomorrow	If there is at least 1mm of rain tomorrow	Yes/No	object
