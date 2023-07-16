# ML_Project2
Census Income analysis with Classification model created using Machine Learing Algorithms using Python

I got Census Income data which contains several features. As it was not fit for directly creating predictive model from the given data,i have to make it to go through data preprocessing process.
1.Listed out the features name,their datatypes, number of unique values and number of null values in each of the columns.
2.As Education and Education.num columns have exactly one to one to correspondance,removed education column.

Now, used training data for creating predictive models.
1. LogisticRegression
2. DecisionTreeClassifier
3. RandomForestClassifier
4. GradientBoostingClassifier
5. XGBClassifier
6. MLPClassifier(Neural network)
7. KNeighborsClassifier
8. SVC(Support Vector Classifier)
9. Naive Bayes
10. Stacking of 7 different models

After fitting data into these above models,got some roc_auc_Score for each of these models.
[['LogisticRegression', 0.8201600843951002],
 ['DecisionTreeClassifier', 0.8167600833708879],
 ['RandomForestClassifier', 0.8247676958294072],
 ['GradientBoostingClassifier', 0.8365396088532918],
 ['XGBClassifier', 0.835611480396575],
 ['NeuralNetwork', 0.5128322929042567],
 ['KNeighborsClassifier', 0.6260010395755664],
 ['SVC', 0.5128747977180548],
 ['Naive_bayes', 0.6004818919251096],
 ['stacking', 0.8404280311565406]]
 
 As stacking gives the highest roc_auc score, created a model for stacked algorithm.
