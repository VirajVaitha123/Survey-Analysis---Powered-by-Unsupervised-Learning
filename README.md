# Survey Analysis - Powered by Unsupervised Learning


![Test](https://github.com/VirajVaitha123/Survey-Analysis---Powered-by-Unsupervised-Learning/blob/master/Images/Phone.png)


#### Introduction

Analysing survey results can be challenging. It's common for customers to experience similar experiences leading to groups of individuals selecting the same survey responses. However, they won't all select the same as people are interested in different things. For example, some go to a restaurant for atmosphere whilst others go primarily for the food. Clustering can help us gain a general concensus of our customers.

Clustering is an unsupervised machine learning method. Unsupervised techniques don't require labelled data (it doesn't need us humans to teach the model directly). This notebook will focus on clustering customer survey responses from an airline. This analysis could be used on any surveys that use a numerical scale.
<br>
<br>
#### Methodology

Create a real life scenario to make the randomly generated data more meaningful and easier to follow.

An airline company would like to analyze survey results at scale. This could help the company identify loyal customers and improve the retiontion of non loyal customers.

##### 1. Design the Survey

Please note that it's important for each response to be on the same scale. An airline has been collecting feedback from their customers through their app. It's important for the executive team at the airline to understand the reponses to provide improvements to the airline.


0 - Strongly Disagree <br>
1 - Disagree <br>
2 - Neutral <br>
3 - Agree <br>
4 - Strongly Agree 

Lastly, you must include the fundamental question:
"I would return to "ABC" in the future"

##### 2. Import the data 
In this case I randomly generated data as this I wanted to test if this analysis would gain insights before carrying out an actual survey on a large number of people.

##### 3. Apply the Elbow Technique to determine the appropriate number of clusters 
To make this step dynamic in the future, we should write some code to automatically select the suitable number of clusters.
Currently we are plotting a graph and manually selecting the best number of clusters.
Instead, we would "plot a graph" and write code to approximate the correct number of K to remove manual intervention.

##### 4. Predict and attach the clusters for each persons survey

##### 5. Create an Interactive Dashboard
<br>
<br>
An example dashboard I have created can be seen below:
<br>
<br>

##### Contents of the ntebook
1. Import relevant packages
2. Creating the raw data (dataframe)
3. Unsupervised Learning (KMeans) - Elbow Method to determine K
4. Unsupervised Learning (KMeans) - Predict Cluster
7. Output clusters into dataframe 
8. Visualise results
9. Export to PowerBI and Visualise results
11. Discussion
12. Conclusion
