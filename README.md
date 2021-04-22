# ACMW-Task
ML Task 
The aim of the my first task is  project the wine dataset from a higher-dimensional space to a lower one while keeping most of the relevant information, that would make it a lot easier for us to study the data.
I have used Jupyter notebook for the task and have used libraries like numpy,pandas,matplotlib,seaborn and skylearn.Firstly,I imported the wine dataset into the program.Then,I standardised the values so as to apply dimensionality reduction on it.The major step included calculating eigenvectors and corresponding eigen values,arranging them in descending order and finally selecting the top eight corresponding eigen vectors.Then,finding the eigenvector matrix W with dimensions as 13X8.Following this,I project the original dataset on matrix_W and then,convert the ndarray into dataframe.This completes the dimensionality reduction giving us a dimensionally reduced dataframe with 8 attributes.A heat map is also plotted for this data, henceforth. 

The second part involves classifying the data into three clusters numbered as [0,1,2] for which I have used the K means clustering.

For third part which involves comparing the members of formed cluster and the members of pre-exising class label,I read this data into a csv file and on sorting,I find that most of the members of :
"Class Label 1" are put in Cluster2.
"Class Label 2" are put in Cluster0.
"Class Label 3" are put in Cluster1.
Thus,I just change the name of the clusters under the column Modified Cluster No.Then,using accuracy_score function,I predict the accuracy achieved by k means clustering and that comes out to be 70.224%.
