
# Customer Type Prediction
# Inspiration ![image](https://user-images.githubusercontent.com/72274851/218500470-ec078b99-0a50-4b06-a2df-c09e47ecc187.png)
In the hospitality industry, understanding the type of customer visiting a hotel is crucial for providing tailored services and creating effective marketing strategies. Customers have different preferences and needs, depending on their purpose of visit, such as business or leisure travel, group or individual stay, etc. Therefore, predicting the customer type accurately can provide valuable insights for hotel managers and marketers to optimize their services and increase customer satisfaction.

This problem can be solved by applying machine learning techniques to the available data related to the customer and the hotel. By creating a predictive model, the hotel can categorize customers into different types, enabling them to offer personalized services and experiences. This project can serve as a reference for similar classification problems in the hospitality industry or other industries that require customer segmentation.


![Logo](https://imgs.search.brave.com/_fc5DAgvLKh52OMh1nSRtG_AEetAtSM4Fe3O8tncfpQ/rs:fit:800:600:1/g:ce/aHR0cHM6Ly9pcnAu/Y2RuLXdlYnNpdGUu/Y29tLzM1NWZiOGI0/L2RtczNyZXAvbXVs/dGkvY2xpZW50ZS02/YTUxZWZmMS5naWY.gif)


## Problem 
The problem is to **predict the type of customer visiting a hotel** based on various attributes related to the customer and the hotel. The classification of the customer type could be a contract, transient, group, etc. The accurate prediction of the customer type can help hotel managers and marketers to customize their services and marketing strategies to meet the specific needs of their customers.
## Solution
The solution is to create a machine learning model that can predict the customer type based on the available data. The data preprocessing steps involve data cleaning, feature engineering, and normalization. **The model selection process includes choosing appropriate algorithms such as SVM, Logistic Regression, MultinomialNB, KNeighborsClassifier, GradientBoostingClassifier, GaussianNB, DecisionTreeClassifier**. The evaluation metrics for the models could be accuracy, precision, recall, and F1 score. The feature importance analysis could reveal which attributes have the most significant impact on the prediction. The trained model can be used to predict the customer type of new customers. This project provides a reference for similar classification problems in the hospitality industry and beyond.
## Conclusion of the analysis
As we worked with the different types of models that have trained for predicting the solution of the problem, **DecisionTreeClassifier model predict more accurate** and can able to classify the customer. Based on the datas provided by the hotels the model is trained and the new datas can be predicted.

## Models used
- svm
- Logistic Regression
- MultinomialNB
- KNeighborsClassifier
- GradientBoostingClassifier
- GaussianNB
- DecisionTreeClassifier
## Part of OneAPI in prediction
![Logo](https://imgs.search.brave.com/Q6pMW0O05cYYhIrRbG-ZqwfTgwJdv6brDVxG7jdD9Vk/rs:fit:965:543:1/g:ce/aHR0cHM6Ly93d3cu/YWxjZi5hbmwuZ292/L3NpdGVzL2RlZmF1/bHQvZmlsZXMvc3R5/bGVzLzk2NXg1NDMv/cHVibGljLzIwMjAt/MDYvMTY1MTktMV9J/bnRlbF9vbmVBUElf/UHVibGlzaGVyQmFu/bmVyXzNfdjAuMWJf/cmVzaXplZC5qcGc_/aXRvaz1DUUh4d2dm/Xw)
OneAPI is a unified, cross-architecture programming model and software development platform developed by Intel to simplify application development across diverse computing architectures. Its main purpose is to enable developers to write applications that can run efficiently on a variety of computing devices, including CPUs, GPUs, FPGAs, and other accelerators, without the need for extensive code modifications or rewrites.

With OneAPI, developers can use a common set of programming interfaces, libraries, and tools to create high-performance applications that can take advantage of the full computing power of a heterogeneous hardware environment. This makes it easier to optimize applications for specific hardware platforms and reduce the time and cost of developing, testing, and deploying software across different architectures.

In this prediction model the **accuracy of the code is increased** compared to my local machine and which is one of the important thing about the model creation. By this OneAPI platform I can use it on **different kind of machines** which ensures the **cost efficient** of the project.
##DevMesh Link ==> https://devmesh.intel.com/projects/customer_type_prediction_using_oneapi
