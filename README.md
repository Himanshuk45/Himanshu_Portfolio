# Himanshu_Portfolio
This portfolio contains my data science projects

# [Project 1: Credit Card Fraud Detection: Project OverView](https://github.com/Himanshuk45/Himanshu_Portfolio/blob/main/CreditCard_FraudDetection.ipynb)
- Used python and machine learning algorithms to build a credit card fraud detection model. <br />
- Used matplotlib to create histograms and scatter plots to visualize the dataset. <br />
- Used seaborn to inspect the heatmap of the correlation matrix of the different variables. <br />
- Used three different algorithms to build the anomaly detection model: Isolation Forest, Local Outlier Factor & One Class Support Vector Machine. <br />
- Analyzed the result from all the three algorithms and concluded that Isolation Forest has an overall better accuracy score than the other two algorithms.

**The following histogram shows that the dataset is highly imbalanced with very few numbers of fraudalent cases as compared to normal cases:** <br />
<img src="https://github.com/Himanshuk45/Himanshu_Portfolio/blob/main/Images/index.png" class="img-responsive" alt=""> </div>

<br />
**Even the amount of money that's involved fraudalent cases is much smalle than normal transactions:**
<img src="https://github.com/Himanshuk45/Himanshu_Portfolio/blob/main/Images/index1.png" class="img-responsive" alt=""> </div>
<br />
**The following heatmap of the correlation matrix shows that the various variables aren't strongly correlated:**
<img src="https://github.com/Himanshuk45/Himanshu_Portfolio/blob/main/Images/index4.png" class="img-responsive" alt=""> </div>
<br /><br />
Finally, here's the conclusion about the different algorithms that I used to build a model:<br />
- Isolation Forest detected 73 errors, Local Outlier Factor (LOF) detected 97 errors while SVM detected 8516 errors.
- Isolation Forest has an accuracy score of 99.74% as compared to the 99.65% accuracy score of LOF and 70.09% score of SVM.
- When comparing error precision & recall for 3 models , the Isolation Forest performed much better than the LOF and SVM models.
