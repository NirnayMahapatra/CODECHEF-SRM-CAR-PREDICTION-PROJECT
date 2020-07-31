# CODECHEF-SRM-CAR-PREDICTION-PROJECT
it is a project in which we have to predict the buying price of a car using machine learning algorithms.
We are given a train dataset and test dataset in the form of csv(Comma Separated Value)files.
Shape of train dataset is (2000,13).
Shape of test dataset is (509,11).
The target varibale in this problem is buying_price.
We have to predict the buying_price for test dataset
i have concatenated the train and test dataset into one dataframe df.libraries used in the code: numpy, pandas, matplotlib, statsmodel
Then i have used the function data,describe percentiles to find the percentile of the given data set.
Then for cleaning the data i have used data.duplicate and no duplicate items wer found.
I have counted all the values of 'on road old' , 'on road now' and the rest of all the data which were their in the given dataset.
By using the library of sns.distplot i hav eplotted the graph of 'buying price' , 'economy' , 'rating'.
Then for data visualisation i have used sns.pairplot so scattered graph is formed of the data.
Then I have plotted the heatmap using the seaborn library to analyse which features contain the null values graphically.
