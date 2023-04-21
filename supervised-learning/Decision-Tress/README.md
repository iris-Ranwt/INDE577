# Decision Tree

## Objectives

In this part we would discuss about decision tree. A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes.

## Dataset Description 

### Overview
We would use dataset of Tianic from kaggle in this assignment and performing the decision tree and the data has been split into two datasets:

*  training set (train.csv)  
*  test set (test.csv)   

The datasets contain of:  
* survival:	Survival	0 = No, 1 = Yes  
* pclass:	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd  
* sex:	Sex	  
* Age:	Age in years	  
* sibsp:	number of siblings / spouses aboard the Titanic	  
* *parch:	number of parents / children aboard the Titanic	  
* ticket:	Ticket number	   
* fare:	Passenger fare	   
* cabin:	Cabin number	   
* embarked: Port of Embarkation. C = Cherbourg, Q = Queenstown, S = Southampton 

 The training set is be used to build the models, as it provides the outcome for each passenger. The test set is be used to see how well the model performs on unseen data.
  
   
## Packages
The following packages will be needed to run the code below:
*   matplotlib: [documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
*   numpy: [documentation](https://numpy.org/devdocs/)
*   pandas: [documentation](https://pandas.pydata.org/docs/)
*   sklearn: [documentation](https://scikit-learn.org/stable/)


## Reference 
* What is decision tree, IBM, https://www.ibm.com/topics/decision-trees#:~:text=A%20decision%20tree%20is%20a,internal%20nodes%20and%20leaf%20nodes.  
* Kaggle dataset, https://www.kaggle.com/competitions/titanic/data?select=test.csv 
* Decision Tree - Classification, https://www.saedsayad.com/decision_tree.htm 