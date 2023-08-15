# Advanced Analytics & Dashboard Design Project

## Tittle Annalysis On Gun-violence in US 01-2013_03-2018
## <font color='blue'> Author Angela North</font>

# <a id ='1'> 6.0 Motivation & Introduction </a>


Some people believe that the rate of gun violence in the United States has dropped, however over the past half-century, both the frequency of mass shootings that were planned in advance and the severity of each shooting have increased. For instance, the notorious massacre that took place at the Columbine high school in 1999 was a well organized assault that resulted in the deaths of 13 people and injured 25 more. Stephen Paddock, the suspect in the mass shooting that took place in Las Vegas in 2017, opened fire at a concert on October 1 of that year. There were around 58 people who passed away, in addition to roughly 500 others who were injured. The shooting rampage that took place in Las Vegas is currently considered to be the deadliest incident in recent memory. Therefore, given that there is a trend toward a larger size for each mass shooting as well as other statistics that indicate the scale of everyday gun violence, the assertion that gun violence is decreasing looks doubtful. This is because there is an upward trend in magnitude for each mass shooting. As a result, my business partner and I are interested in conducting additional research into the problem of gun violence in the United States in the hopes of unearthing some potential facts.

The importance of conducting research on gun violence lies in the fact that it has the potential to enhance our existing understanding of the subject of gun violence in the United States. Aside from that, it can assist in the determination of a variety of other enlightening information, such as the place with the highest rate of gun violence, the collateral damage that is created by gun violence, and a great deal more. As of right now, our working hypothesis is that the rate of gun violence is higher than it has ever been; hence, our primary objective is to conduct an in-depth investigation into this concept. During the course of our exploratory data research, we intend to gain a more comprehensive understanding of the factors that contribute to gun violence in the United States and arrive at a number of shocking findings regarding the current status of gun violence.

# <a id='2'> 6.1 Sourcing Open Data</a>

# About Dataset
### Context
There's currently a lack of large and easily-accessible amounts of detailed data on gun violence.

### Content
This project aims to change that; we make a record of more than 260k gun violence incidents, with detailed information about each incident, available in CSV format. We hope that this will make it easier for data scientists and statisticians to study gun violence and make informed predictions about future trends.

The CSV file contains data for all recorded gun violence incidents in the US between January 2013 and March 2018, inclusive. https://www.kaggle.com/datasets/jameslko/gun-violence-data?select=gun-violence-data_01-2013_03-2018.csv

### Acknowledgements
#### Where did you get the data?

The data was downloaded from gunviolencearchive.org. From the organization's description:

Gun Violence Archive (GVA) is a not for profit corporation formed in 2013 to provide free online public access to accurate information about gun-related violence in the United States. GVA will collect and check for accuracy, comprehensive information about gun-related violence in the U.S. and then post and disseminate it online.

#### How did you get the data?

Because GVA limits the number of incidents that are returned from a single query, and because the website's "Export to CSV" functionality was missing crucial fields, it was necessary to obtain this dataset using web scraping techniques.

Stage 1: For each date between 1/1/2013 and 3/31/2018, a Python script queried all incidents that happened at that particular date, then scraped the data and wrote it to a CSV file. Each month got its own CSV file, with the exception of 2013, since not many incidents were recorded from then.

Stage 2: Each entry was augmented with additional data not directly viewable from the query results page, such as participant information, geolocation data, etc.

Stage 3: The entries were sorted in order of increasing date, then merged into a single CSV file.

#### Inspiration
I believe there are plenty of ways this dataset can be put to good use. If you have an interesting idea or feel like messing around with the data, then go for it.

I was originally inspired to compile it in the wake of the Parkland shooting and the mass media coverage that followed. Reports like this and this showed that Nikolas Cruz had exhibited plenty of warning signs on social media before the shooting; what if we could build a machine learning system that preemptively detected such signs?

* ● Source the data you’ve chosen for your project by adhering to the requirements stated in
  the project brief.*

* ● Complete preparatory steps before moving on to analysis (e.g., cleaning).*

* ● Define questions to explore based on your understanding of what the data contains.*

* ● Create a document containing details of initial preparatory steps conducted.*

# Exploring Relationships

* ● Conduct exploratory visual analysis using relevant Python libraries.*
* ● Use the questions you defined in the previous task to guide your exploration.*
* ● If possible, define hypotheses to test.*

# Geographical Visualizations with Python

* ● Source a shapefile containing location data that corresponds to the location data in your
  main project data set.*

* ● Conduct a geospatial analysis by creating a choropleth map using relevant Python
   libraries.*
* ● Wrangle, clean, and merge data files in preparation for analysis.*


# Unsupervised Machine Learning: Clustering

* ● Prepare your data for a cluster analysis.
* ● Use the elbow technique to determine the optimal number of clusters.
* ● Run the k-means algorithm.
* ● Attach a new column to your dataframe with the resulting clusters.
* ● Create a variety of different visualizations using your clustered data.
* ● Calculate the descriptive statistics for your clusters using the groupby() function and
    discuss your findings and any proposed next steps.

# Sourcing & Analyzing Time Series Data

* ● Source time-series data relevant to your project data via an API.
*  ● Subset your data if necessary so that it contains only relevant historical data.
 * ● Visualize the data in a line plot and decompose its structure.
*  ● Conduct a Dickey-Fuller test and plot autocorrelations to test for stationarity.
 *  ● Perform differencing to stationarize non-stationary data.

# Creating Data Dashboards

* ● Define the use-case for your dashboard.
* ● Outline dashboard contents based on curated results of analysis.
* ● Create dashboard/storyboard in Tableau per the requirements in the project brief.
* ● Publish your storyboard to Tableau Public.
* ● Create a portfolio-ready GitHub repository for your project per the requirements above in
    the project brief.


```python

```
