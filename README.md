# Credit-Card-Fraud-Detection
Built a Credit Card Fraud Detection system using Logistic Regression and Random Forest Classifier,I have compressed the data set in a rar file beacuse it exceeded the GitHub limit of 100MB,to build this system I used standard scalar to standardize the "Amount" Columns in the data set because the fraud transaction amounts were much lower than the genuine transaction amounts so we needed to scale them,upon using the Logistic Regression model for classification the acurracy was very high,but the precision and recall score were low,so I used the Random Forest Classifier Model to classify and detect fraud Transactions,this works because Tree based classifiers are good for imbalanced data,which is the case here.In the data set the number of Genuine transactions are much more than then the fraud ones so we call it imbalanced data,thereafter to to further optimize my model I used K-Fold Cross validation technique,which improved the performance quite a bit,thereafter to further optimize my model I used Artificial Neural Network,it performed very good,but did not help much,the K-Fold estimations were found to be better.

 ********important************
 
 
**Note:I usually visualize my data by using Plotly Library,so if you are having trouble viewing them in the GitHub viewer, you are free to clone my repository on your local machine and check them out in jupyter notebook,other wise follow the step below.

***********Please copy the Notebook URL and paste it on:-http://nbviewer.jupyter.org/

                ******Peace Out*******
