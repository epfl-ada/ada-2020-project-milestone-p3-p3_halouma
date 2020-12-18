# Title
Comparing racial disparities in police stops in blue and red states

# Abstract
We would like to put the paper into perspective. It dates from 2016 which is also the year Donald Trump was elected President of the United States. As D.Trump is criticised for the discrimination he embodies, we wonder to what extent political ends reflect discrimination or vice versa. Therefore, we will see if there is a correlation between the states' major political party (Republican or Democrat) and racial disparities observed initially in the paper.
We will use a new dataset: the electoral map of the 2016 Presidential election, indicating the winning color of the state (blue for Democrat and red for Republican). In these two types of states, we extract the race of stopped drivers, as well as whether a search was conducted and if contraband was found to study the hit rate and threshold - as done in the paper. We compare results in the two groups of states thanks to different methods explained in the corresponding section of this document. We would like to perform this analysis to determine whether a state's political party can be correlated with racial bias in the police stops. This is all the more interesting because the police behaviour can be an indicator of a tense climate between groups of individuals. 
The police comprise a large number of officers and they are confronted with all groups of individuals. Studying their behaviour can be a barometer of prejudices between different ethnic origins - the correlation with any political inclination would be even more worrying about the values spread by certain political parties.

# Research Questions
Is there a correlation between racial bias in police stops and the political orientation of the region ? We would like to investigate this by comparing the hit rates and thresholds in blue and red states respectively, and then at a county level, thanks to different approaches.
We will conclude by saying whether there are disparities according to the major political orientation of the state or county. We will present the possible explanations for our results and try to draw clear conclusions.

# Proposed dataset
  1. The electoral map of the 2016 presidential election (https://www.nytimes.com/elections/2016/results/president). We will pick at least one state per major political party based on the criteria "places that tend to vote much more democratic" or "places that tend to vote much more republican". For now, we plan to choose Massachusetts, Vermont, Rhode Island and/or New Jersey for blue, and Texas, South Carolina and/or Montana for red.
  2. The dataset from the article. We will extract the race, sex, search conducted and contraband found criteria with objective of observing hit rates. For each state, we will use the State Patrol data as this should be representative of an entire state's distribution of stops. This is important because we observed that even in highly republican states big cities tend to vote democratic.
We will use the dataset of the article from the paper's website https://openpolicing.stanford.edu/data/. It allows us to identify states whose state patrols have recorded the necessary data and make sure we assess an equivalent number of police stops for blue vs red states. The data files are in the form of CSV and are therefore easily manipulated using Pandas. We can then merge the filtered data into two dataframes, one for blue states and one for red states, for example.

# Methods
Our approach consisted in: 
 - performing a first visualization of the data studied
 - reiteration of the tests performed in the paper, separating red and blue states
 - analysis of these first results
 - carry-out of statistical mean comparisons to make these comparison more robust
 - adding information about the purcentage obtained by the parties for more precise results
 - training of model prediction: allows to evaluate the weight of the political parameter in the estimation of the hit rate or threshold for a specific driver in a specific state
 - analysis of these results and orienting the next steps according to them
 - reiteration of these steps at the county level for each counties in Texas. This allows to obtain more precise information about political inclination
 - try to find explanations to our results by other approaches: study of a inversed correlation between the county number of searches and the hit rates and threshold.
 - finding other explanation or bias to our results to widen our vision
 - drawing conclusions
 
# Proposed timeline
  1. By December 4th: we found our needed datasets and processed them for analysis
  2. By December 8th: we finished the individual part of the replication and were ready to start the extension
  3. By December 15th: we had coded the different steps of our projects. We started the data story.
  4. By December 18th: Data story and analysis of our findings done. First deliverable ! We start the video.
  5. By December 21st: we hand-in our video and finish our project !
  
# Organization within the team
Referring to the timeline above:
  1. 1st milestone: Louis and Margaux
  2. 2nd milestone: Everyone worked on their individual part. Hannah and Margaux adapted it to our extension.
  3. 3rd milestone: Louis, Margaux and Hannah. Louis performed the data verification and visualization, Hannah performed the statistical tests, Margaux extended and adapted all our approach to the study of counties. Hannah started the squeletton of the data story website, while the others finished the analysis at the county level. Then everyone worked together to clean and comment the code, fill the website with our findings and explain them.
  4. 4th and 5th milestone: everyone worked on analysis by discussing together. The video is prepared together as well.

# Our datastory
Want to check out our website and learn about racial disparities in red and blue states ? Follow [this link] (https://mfroute.github.io/) and don't forget to tell us all about what you thought at [our email adress] (halouma@epfl.ch) !

# Our notebook
Our full approach with our code and the details about our parameters, statistical methods et cetera is available [here] (https://github.com/epfl-ada/ada-2020-project-milestone-p3-p3_halouma/blob/main/extension.ipynb).