# Student-Classfication_Task
Machine learning Applications

I have used the students dataset and applied various machine learning algorithms on it.

Target variable is Grades

Step1: Done preprocessing of data i.e imputing NA's , changing categorical values into one hot vectors and binary values and removing unwated row/columns

Used MinMax Scaler to scale the dataset

Methods Used:

1. SoftMax Regression Method with following HyperParameters : #solver= 'lbfgs' 
#multi_class='auto' 
#max_iter=1000 
#random_state = 0

2. Logistic Regression Method with following HyperParameters and conditions: 
#Assume letter grades 'A', 'B', and 'C' are passing grades. 
#Turn this dataset to a binomial dataset by considering grades as 'Pass' and 'Fail'. 
#multi_class='auto' 
#max_iter=1000 
#random_state = 0

3. SVM method with following HyperParameters and conditions:
#random_state = 0 
#kernel = 'rbf' 
#gamma = 0.1
#C = 1

4. Made confusion matrix to figure out How many instances with grade 'B' (3) in the test dataset are predicted correctly by this model



5.Decision Tree Classifier Model with following HyperParameters and conditions:


#max_depth=2 
#random_state=0 
#criterion='entropy'
