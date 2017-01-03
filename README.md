# R_Projects
<b>Project 1 Description:</b>
1. Data Set: Enron Mail Subset (on Blackboard)
a. Extract the following fields: From, To, Date, Subject, and Message ID

Of the 26 people listed, there are connections among many of them. But, you need to find these by processing the email in their folders.
.
So, writing a function to open maildir, and iterate over people. It will call a function to iterate over their subfolders. Each contains a file “1” which is a mail message. Extract the relevant data and store it someplace.

2. Graph Analytics: once you have extracted data from the text messages, and assembled it in one or more data structures, you will need to build graph representation. You should do this as a matrix. You should have at least 20 people in your graph; more would be nice.

3. Deliverables: You will deliver, by putting a zipfile in your group’s Blackboard file, with the following naming convention: Group-N-Project-1.zip, where N is your group number. Your deliverable should encompass the following items:

•	A listing of all R functions that you have written
•	A document listing the people in your graph, the number of edges – indegree and outdegree – for each person
•	The matrix of the graph in a word document
•	Computation of the following metrics:
o	The central persons in your graph (there may be more than one)
o	The betweenness metric for all persons in your graph
o	The prestige of each node


a.I wrote the R functions
b.I found person listing with # edges in and out.
c.The matrix g with row and column labels, g2 = g %*% g, showing maximum path length.
d. Who is the central person in your graph? .
5. Identified the metrics centrality, betweenness and prestige metrics.

<b>Project 2 Description:</b>

Exploring Variations in Clustering Analysis

1. Data Set: Mushroom Data Set (on Blackboard)
The problem is to determine what makes a mushroom edible or not-edible. This data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family (pp. 500-525). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like ``leaflets three, let it be'' for Poisonous Oak and Ivy.

There are 8124 records with 22 attributes, some having missing attributes.

You will need to divide your data set into a training set and a test set. Use samples of 50-50, 60-40, and 70-30 for the training-test ratios

Try plotting the data using several plotting functions to see what it looks like. Use pairs or 3 variables based on the packages. 

Try to filter the data by selecting samples with only certain attribute values and plotting them.

We discussed a number of techniques in the last two classes and you can use other techniques from the contributed R packages.

2. This will involve some statistical analysis and some clustering. Use the r packages and functions in the notes as well as the ones below. 

3. Deliverables: You will deliver your results by putting a zipfile in your group’s Blackboard file, with the following naming convention: Group-N-Project-2.zip, where N is your group number. Your deliverable should encompass the following items:

A listing of all R functions that you have written
•	A document giving your results which should include:
a. a clustering of the samples into 2 (edible or poisonous) classes using three different clustering methods, such KMeans, nearest neighbor, one other
b. a clustering of the samples into N = 3, 5, 7 classes using three different clustering methods, such KMeans, nearest neighbor, one other with number of points per cluster
c. prepare a table containing the data from (a & b) with the three training-test ratios for each of the N and each clustering method
d. plots using several methods in lectures 4 and 5.

You should investigate some of the statistics of the data set

See the trimkmeans package, akmeans package, kknn package, FNN package

Part b is a simple version of doing a Monte Carlo investigation in one parameter.

You may have to do conversion your data sets to numerical values. I already showed you how to do this in one case.

You should determine what to do and divide the work up among the team members after creating the different training and test subsets.



a. Document R functions: 
b. Matrix with results as specified in 3 above: 5 points
c. Discussion of results from the experiments that you run in part 3b above. Which clustering version gives the best results? What seems to be the best number of clusters for each method? --- 3 points
d. Plots with discussion of results: which plot helped you understand the data best and why? – 3 points
e. Analysis of what this project helped you learn about data science, e.g., the exploration of data which is what you have been doing.

<b>Project 3 Description:</b>

Working with Machine Learning Algorithms
In R

1. Data Set: Mushroom Data Set (on Blackboard)
The problem is to determine what makes a mushroom edible or not-edible. This data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family (pp. 500-525). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like ``leaflets three, let it be'' for Poisonous Oak and Ivy.

There are 8124 records with 22 attributes, some having missing attributes.

2. You will use the three ML techniques that I included in Lecture 9: rpart, C50, and randomForests. The objective is to determine if these techniques can distinguish between the two types of mushrooms. Download the three packages and their package descriptions. You will also need to use some of the functions to explain the results, and rpart.plot to plot some of the data for rpart.

3. Deliverables: You will deliver your results by putting a zipfile in your group’s Blackboard file, with the following naming convention: Group-N-Project-2.zip, where N is your group number. Your deliverable should encompass the following items:

A listing of all R functions that you have written
A document giving your results which should include you assessment of how well the three techniques work in distinguishing edible versus poisonous mushrooms, presentations of your results from the three programs, and any plots or other visual presentations.
 
You should investigate some of the statistics of the data set


a. Document R functions
b. Presentation and discussion of results from the experiments that you run using the three techniques:  Which technique gives the best results? Why?
c. Plots where applicable should be included in b.
d.I did analysis of what this project helped you learn about data science, e.g., the exploration of data which is what you have been doing.

<div class="LI-profile-badge" data-version="v1" data-size="medium" data-locale="en_US" data-type="profinder" data-theme="light" data-vanity="arpithparikh"><a class="LI-simple-link" href="https://www.linkedin.com/profinder/pro/arpithparikh?trk=profinder-badge">Arpit Parikh</a></div><script type="text/javascript" src="https://platform.linkedin.com/badges/js/profile.js" async defer></script>



