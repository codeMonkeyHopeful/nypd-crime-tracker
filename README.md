# NYPD Hate Crime Tracker

A simple Python analysis of NYPD hate crime data by area through the year 2020. Aim is to see if any trends exist in the hate crimes as the city went through drastic changes due to Covid-19 and mass fear that the nation faced.

### Dataset

The data used for this analysis is open to the public via NYC Open Data website [here](https://data.cityofnewyork.us/Public-Safety/NYPD-Hate-Crimes/bqiq-cu78) and if so desired pulled directly into your project through their API route directly, [here](https://data.cityofnewyork.us/resource/bqiq-cu78.csv).

### Data Dictionary

This table describes the available data from the provided dataset. Some data has been renamed and other not used in this particular analysis.

| Column Name                   | Description                                    | Data Type |
| ----------------------------- | ---------------------------------------------- | --------- |
| Full Complaint ID             | Identifier for each hate crimes incident       | Text      |
| Complaint Year Number         | Year in which incident occurred                | Text      |
| Month Number                  | Month in which incident occured                | Integer   |
| Record Create Date            | Date report was filed                          | Datetime  |
| Complaint Precinct Code       | NYPD Precinct in which incident occurred       | Integer   |
| Patrol Borough Name           | NYPD Patrol Borough in which incident occurred | Text      |
| County                        | County in which incident occurred              | Text      |
| Law Code Category Description | Category of offense                            | Text      |
| Offense Description           | A description of the offense                   | Text      |
| PD Code Description           | The NYPD description of the offense            | Text      |
| Bias Motive Description       | NYPD category of hate crime or bias type       | Text      |
| Offense Category              | General categorization of hate crime type      | Text      |
| Other Motive Description      | Additional motive for offense                  | Text      |
| Arrest Date                   | Date arrest was made (if arrest happened)      | Datetime  |
| Arrest Id                     | Identifier for arrest (if made)                | Text      |

### Data Used

The data selected for this analysis is related to location, crime type, and time span. From these basic data points we are able to do differnt cuts to discover trends across which crimes were more prevalent, where, and any fluctuations in said crime frequencies.

### Data Methods Used

Generally the strategy in the analysis was to cut the desired data from the main source ex. location and crime type, aggregate the results in different ways, and plot out to see what we are able to find. Notably we rename, rank and count our the values, filtering to what is needed before plotting.

### Challenges

Any challenges encountered

### Take Aways

A few key insights you derived from your analysis
Conclusion(s) / key takeaways from your analysis
