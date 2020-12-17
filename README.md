# Title
Comparing racial disparities in police stops in blue and red states

# Abstract
We would like to put the paper into perspective. It dates from 2016, the year Donald Trump was elected President of the United States. As Trump is criticised for the discrimination he embodies, we wonder to what extent political ends reflect discrimination or vice versa. Therefore, we will see if there is a correlation between the states' major political party (Republican or Democrat) and the race of the drivers searched. 
We will use a new dataset: the electoral map of the 2016 Presidential election, indicating the winning color of the state (blue for Democrat and red for Republican). In these two types of states, we will extract the race of stopped drivers, as well as whether a search was conducted and if contraband was found to study the hit rate and threshold - as done in the paper. That done, we will compare results in the two types of states thanks to different statistical methods. We would like to perform this analysis to determine whether one's political party can be correlated with racial bias. This is all the more interesting because the police behaviour can be an indicator of a tense climate between groups of individuals. 
The police comprise a large number of officers and they are confronted with all groups of individuals. Studying their behaviour can be a barometer of prejudices between different ethnic origins - the correlation with any political inclination would be even more worrying about the values spread by certain political parties.

# Research Questions
In our project we would like to find out whether there is a correlation between racial bias and political orientation of the region, by comparing the hit rates and thresholds in blue and red states respectively.
We will try to conclude by saying whether there are disparities according to the major political orientation of the state and on which criteria.

# Proposed dataset
  1. The electoral map of the 2016 presidential election (https://www.nytimes.com/elections/2016/results/president). We will pick at least one state per major political party based on the criteria "places that tend to vote much more democratic" or "places that tend to vote much more republican". For now, we plan to choose Massachusetts, Vermont, Rhode Island and/or New Jersey for blue, and Texas, South Carolina and/or Montana for red.
  2. The dataset from the article. We will extract the race, sex, search conducted and contraband found criteria with objective of observing hit rates. For each state, we will use the State Patrol data as this should be representative of an entire state's distribution of stops. This is important because we observed that even in highly republican states big cities tend to vote democratic.
We will obtain the dataset of the article from the paper's website https://openpolicing.stanford.edu/data/. It allows us to identify states whose state patrols have recorded the necessary data and make sure we assess an equivalent number of police stops for blue vs red states. The data files are in the form of CSV and are therefore easily manipulated using Pandas. We can then merge the filtered data into two dataframes, one for blue states and one for red states, for example.

# Methods
Our approach consisted in: 
  - creating adapted datasets by including the color of the state (blue or red for democratic and republican party)
  - checking that we had enough information with a large enough number of police searches to study
  - a primer visualization of the hit rates and threshold for police searches in blue and red states respectively
  - comparing those parameters thanks to statistic tests for mean difference and to model prediction and analysis of the obtained model parameters
  - adding information about election results in counties and proceeding to the same analysis county by county for more precise and accurate results

# Proposed timeline
  1. By December 4th: extract and process all the data for analysis
  2. By December 8th: finished part B and adapt it to the project (hit rate)
  3. By December 11th: finished all the figures
  4. By December 15th: finished results discussion + start video
  5. December 18th: finish video + Project Milestone P4 due

# Organization within the team
Referring to the timeline above:
  1. 1st milestone: Louis and Margaux
  2. 2nd milestone: Hannah and Margaux. Everyone worked on part B.
  3. 3rd milestone: Louis and Hannah
  4. 4th milestone: everyone worked on discussion.
  5. we finish the report and the video together.

# Questions for TAs (optional)
  1. Is our analysis specific enough? 
  2. Should we just focus on just one of racial bias or gender bias and not both?
  3. Is our timeline realistic?
  4. Do you think that using data from just one state per party is enough, or should we use 2 or 3?
