# Forest_Cover_Type_Prediction_Competition

## Code and Resources Used
**Python Version:** 3.7

**Packages:** sci-kit learn, numpy, pandas, matplotlib, seaborn 

**Data Source:** Kaggle dataset of 30m by 30m patch of forest land from the Roosvelt National Forest of northern Colorado posted in 2015. Each patch is
represented as a row in a training set with over 15K observations and test set with over 565K observations. The analysis requires multi-class classification of the test set where each patch of land should be classified as having one of seven forest cover types:

## Data Set Features

The training set includes 54 features excluding “id” plus the target variable “Cover Type”. The test set includes only the 54 features. The data is raw, unscaled and with no null values. A description of the features below:

* 10 numerical: Elevation, Aspect, Slope, Horizontal Distance to Hydrology, Vertical Distance to Hydrology, Horizontal Distance to Roadways, Hillshade 9am, * Hillshade Noon, Hillshade 3pm, Horizontal Distance to Fire Points
* Binary (0 absence or 1 presence) for 4 qualitative wilderness areas: Rawah (area with lower mean elevational value), Neota (area with highest mean elevational value), Comanche Peak (area with lower mean elevational value), Cache la Poudre (area with lowest mean elevational value)
* Binary (0 absence or 1 presence) for 40 qualitative soil type designations
* Numerical (integers 1-7) for 7 qualitative cover type designations