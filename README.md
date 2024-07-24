# FakeJobPosting

1.1 PROBLEM STATEMENT 
The rising cost of living in Malaysia has led to an increase in online fraud cases, particularly job recruitment scams. Many Malaysians, seeking additional income opportunities, fall victim to these scams due to difficulty in distinguishing genuine job openings from fraudulent ones. Current literature compares various machine learning models such as logistic regression, decision trees, random forests, and MLP for detecting fake job postings. However, the trade-off between precision and recall suggests that further refinement and enhancement of these algorithms are necessary to ensure a safer and more reliable job market (Pablo, Guillermo and Alberto, 2023). 

1.2 OBJECTIVES 
-To evaluate the performance of different models. 
-To identify the most suitable model for detecting fake job postings. 
-To enhance the overall performance of classification results, focusing on precision and recall metrics. 

1.3 RESULT & CONCLUSION
This analysis has demonstrated that the Random Forest algorithm provides the best overall performance for detecting fraudulent job postings, excelling in accuracy, precision, recall, and F1-score, while also maintaining a balance between computational efficiency and scalability. Decision Tree and Linear SVC offer advantages in interpretability and deployment simplicity, making them suitable alternatives in contexts where these factors are prioritized. KNN, although accurate, is hindered by high computational costs and scalability issues. SGD Classifier, with its low complexity and high scalability, can be useful in large-scale applications despite lower performance on complex data.

1.4 FUTURE WORK RECOMMENDATION
1. optimizing the selected models to enhance their robustness and efficiency further.
2. experimenting with hyperparameter tuning, feature engineering, and integrating additional data sources to improve model accuracy and generalizability.
3. explore advanced machine learning techniques such as deep learning and ensemble methods to capture more complex patterns in the data.
4. implementing real-time model monitoring and automated retraining pipelines will help maintain the model's performance and adapt to new types of fraudulent activities as they emerge.
5. use larger dataset with real-world data to train the model for improving the model reliability.

By continuously refining our approach, a highly reliable and scalable fraud detection system that can effectively protect users from fraudulent job postings is highly possible to be deployed in the market. 

Contributors: Law(me), Gan, Shafiqah, Spencer, Nazifa
