# Predicting-Future-Sales
Now first we have imported all the necessary libraries for performing certain actions in this project.
We have imported numpy as np for computational mathematics. We have imported pandas as pd to read and work on the data sets. We have imported pyplot from matplotlib and seaborn to visualise the data.
We have imported train and test dataset, so that we can work and fitter model on the train dataset and then after successful in getting the result will feed the test dataset to our model.
There are are shops, item item categories data sets present to give us detail information about the name of the shops the category of the items and the name of the items to get detailed information of the task that we have to perform.
Using describe function we can understand the minimum count and the maximum count of of all the numeric columns of the data and using info function we can understand the data types of the columns.
Now plotting a bar plot with the help of seaborn library, we are going to plot the number of items per item category.
![image](https://user-images.githubusercontent.com/87969705/144179333-2ccbb093-80c3-42fe-b37b-c0eb84d4b2ef.png)
Now understanding the the visualisation, we conclude write the distribution of the number of items per item category is uniformly distributed.
Likewise we plotted the count plot of number of purchases in different days of the month with the help of seaborn. From looking at the graph we can understand that the distribution is slightly skewed right, because the value of number of items distributed from day zero decreases slightly till day 33. Most items purchased were on the eleventh day followed by the twenty third day.
![image](https://user-images.githubusercontent.com/87969705/144180032-790a95fc-bc48-422f-9d28-1229aec0ec33.png)
After this we are going to find out the variation of data distribution in a particular range using distplot. We understand that the distribution of the price ranges from zero till maximum two thousand five hundred. Maximum items were distributed in the price range of zero to one thousand.
![image](https://user-images.githubusercontent.com/87969705/144180892-bee6bec5-ba96-4659-b969-ad54d11c8c11.png)
The following graph shows the distribution of number of items sold per day.
![image](https://user-images.githubusercontent.com/87969705/144181019-5c2df170-6b97-48dd-93bc-607641505293.png)
Now using word cloud we are going to find out the most popular item category among the people.
![image](https://user-images.githubusercontent.com/87969705/144181150-815cd7b3-d047-405b-80c2-ed3245c2b641.png)
We perform similar steps using word cloud to find the most popular item names among the people.
![image](https://user-images.githubusercontent.com/87969705/144181231-4aa8e8d4-15f1-4201-94f9-d28653b95734.png)
We also found out the the most popular shop names using word cloud.
![image](https://user-images.githubusercontent.com/87969705/144181324-b357dbfe-3225-4624-a034-08d50afb9a65.png)
Now we have to find the most busiest days, months, weeks and years for the shops where maximum items were sold. And for that we have to first convert the values in the date column to days, months years, and weeks they were originally in the date format. We executed this operation using dt function.
The distribution of the most busiest days, months and weeks for the shops are uniformly distributed.
![image](https://user-images.githubusercontent.com/87969705/144181638-05e348e1-d16d-49d0-9835-b03a1d2f6d60.png)
![image](https://user-images.githubusercontent.com/87969705/144181917-2cfd49f5-8c42-458e-bc60-6acc73685339.png)
![image](https://user-images.githubusercontent.com/87969705/144181927-c73f0447-56a2-4296-a7e0-3da308407339.png)
The busiest years for the shop was 2013 followed by 2014 and then 2015.
![image](https://user-images.githubusercontent.com/87969705/144181979-ff1f8564-679f-45a9-bae1-eb1040c4aa8a.png)




