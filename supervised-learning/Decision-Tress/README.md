# Decision Tree

## Objectives

In this part we would discuss about decision tree. A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes.

## Dataset Description 

### Overview
We would use dataset of breast cancer from kaggle in this assignment and performing the decision tree:
The main importent variables in the datasets are:  
1. ID number
2. Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:  
1.  radius (mean of distances from center to points on the perimeter)  
2. texture (standard deviation of gray-scale values)   
3. perimeter   
4. area  
5. smoothness (local variation in radius lengths)  
6. compactness (perimeter^2 / area - 1.0)  
7. concavity (severity of concave portions of the contour)  
8. concave points (number of concave portions of the contour)  
9. symmetry  
 10.  fractal dimension ("coastline approximation" - 1) 

   
## Packages
The following packages will be needed to run the code below:
*   matplotlib: [documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
*   numpy: [documentation](https://numpy.org/devdocs/)
*   pandas: [documentation](https://pandas.pydata.org/docs/)
*   sklearn: [documentation](https://scikit-learn.org/stable/)


## Reference 
* What is decision tree, IBM, https://www.ibm.com/topics/decision-trees#:~:text=A%20decision%20tree%20is%20a,internal%20nodes%20and%20leaf%20nodes.  
* Kaggle dataset, https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
* Decision Tree - Classification, https://www.saedsayad.com/decision_tree.htm 