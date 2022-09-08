# TASK-1
The following task is a part of the internship at The Sparks Foundation

The Problem Statement was : To predict the scores of a student based on the number of hours he/she/it studies

Basic Logic of the code-

a) The libraries imported : Matplotlib, numpy, pandas

b) The data contains only 2 variables.

c)The first step includes loading the dataset

d) After loading the same, we need to create a scatter plot out of the same in order to visualize our data.(which includes adding the title, labels, certain modifications,etc)

e) Now, we need to split our data into x and y components, ie : The dependent component(y) and the independant components(y).

f) y includes the scores whereas x includes the hours studies. As, scores = f(number of hours)

g) Now the model is suposed to be trained. Hence, the x component is further sub-divided to : x_train,x_test whereas the y component is also sub-divided to y_test and y-train.

h) Now, this x_train and y_train are used for training the model. Thus, sklearn is imported and LinearRegression is applied.

i) A line(output) and the x,y are plotted to give a comparision.(basically, you are observing the trained model)

j) Now, you will have to test the model. Hence, based on the x_test component, you make certain predictions and store it in y_pred. Hence, y_pred contains the predicted value of the scores obtained when the no. of hrs studied was x_test.

k)You could compare, hence, the actual and the predicted value for y, i.e : y_pred and y_test is compared for x_test.

l) You could further check the mean absol error between the y-pred and y_test as well as you could insert your own data for making predictions.


