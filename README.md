# Survey Analysis - Powered by Unsupervised Learning
Unsupervised Learning

![Test](https://github.com/VirajVaitha123/Survey-Analysis---Powered-by-Unsupervised-Learning/blob/master/Images/Test.png)


#### Introduction

Analysing survey results can be challenging. It's common for customers to experience similar experiences leading to groups of individuals selecting the same survey responses. However, they won't all select the same as people are interested in different things. For example, some go to a restaurant for atmosphere whilst others go primarily for the food. Clustering can help us gain a general concensus of our customers.

Clustering is an unsupervised machine learning method. Unsupervised techniques don't require labelled data (it doesn't need us humans to teach the model directly). This notebook will focus on clustering customer survey responses from an airline. This analysis could be used on any surveys that use a numerical scale.

Please note that it's important for each response to be on the same scale. An airline has been collecting feedback from their customers through their app. It's important for the executive team at the airline to understand the reponses to provide improvements to the airline.




0 - Strongly Disagree <br>
1 - Disagree <br>
2 - Neutral <br>
3 - Agree <br>
4 - Strongly Agree 


<b> Objectives: </b>
- Our key objective is to create a PowerBI dashboard to help us analyse the different trends amoung our customers. Attached final version below:



This notebook focuses on:
- Identifying groups that exist (Automatically finding patterns in our data)
- Visualising our results to learn about our customers
- Assess potentional outliers and assess simpsons paradox
- Intergate cluster outputs into an interactive dashboard


<b> Methodology </b> <br>
1- Create the data ensuring clusters exist <br>
2- Add randomness and noise to the data to mimic real life scenarios<br>
3- Identify the trends you would like the algorithm to detect <br>
4- Apply two different clustering algorithms and determine their performance based on detecting the expecting clusters <br>
5- Visualise the results <br>
6- Export this information to PowerBI and ensure the analysis can be understood by a non technical team


<b> Contents </b> 
1. Import relevant packages
2. Creating the raw data (dataframe)
3. Unsupervised Learning (KMeans) - Elbow Method to determine K
4. Unsupervised Learning (KMeans) - Predict Cluster
7. Output clusters into dataframe 
8. Visualise results
9. Export to PowerBI and Visualise results
11. Discussion
12. Conclusion
