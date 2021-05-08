# Student perfomance predictor

* An ability to predict individual student performance at appropriate points during a module, in particular their likely intermediate and final assessment marks

* This information may then give lecturers and tutors an opportunity to make timely supportive interventions designed to increase the student’s likelihood of success. 

* The identification of students “at risk” of failure or withdrawal has become increasingly important to academics, tutors, support staff and institutions, for a variety of reasons!

This Dataset clearly says about student information including sex , age , address ,famsize ,Pstatus ,Medu ,Fedu ,Mjob ,Fjob ,reason guardian ,traveltime ,studytime ,failures ,schoolsup ,famsup paid ,activities ,nursery ,higher internet ,romantic , freetime,health absences. Data set are provided regarding the performance of students by predicting the final grade !!!

**Data manuplation and exploring**
We will check for all the null values and categorical variables

Find the correlation between the featues in the data and remove the features with high correlation as they might prone you to wrong predictions

Remove if they are any outliers by plotting individual feature box plots

Use label encoding or one hot encoding to convert categorical data to numerical data 

**Regression maximized….**

Here our main target is to find the final grade of students by using the features or parameters , so definetly this is a regression problem as we are producing continuous outputs

So using all the features we apply multilinear regression and predict all the values (y) by taking inputs (x1,x2….xn)

By getting a trend line in a 3d fashion we try to find the weights   (w1,w2….wn,c) and use various other models to find the optimal parameters and obtain less accuracy! 

**Choosing the Best Model ?**

We have experimented on a variety of different models and have finalized our final model as multilinear regression 
As we have a neutralized balance of both rmse and r2score we have choose this model

**A Small Touch Up!!!**

We have converted our best predicting model into a web app so that it is more clear and good for people who don’t want to get their hands dirty

This application will be useful for schools having different branches , so that they can get an analysis on the students grades 











