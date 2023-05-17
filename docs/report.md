#  Masters-Admission-Prediction
##### Presentation Link : https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/blob/main/docs/capstone.pptx
##### Youtube Video Link : https://youtu.be/_Q9k3MyufPQ
# contents
1) Inroduction
2) Dataset
3) Data cleaning and Preprocessing
4) Data Visualization
5) Prediction Models
6) Web Application using Streamlit
7) Conclusion

## Introduction
The admission process for Master's programs is a critical and highly competitive phase for both students and educational institutions. As an aspiring candidate, I have developed a keen interest in exploring the potential of data-driven methodologies to predict the outcome of the admission process accurately. The purpose of this project is to leverage machine learning techniques and historical admission data to create a predictive model that can estimate the likelihood of admission for future applicants.

By developing an admission prediction model, we aim to assist both applicants and admission committees in making informed decisions. For applicants, having an estimation of their admission chances can help them assess their prospects and make well-informed choices about which programs to apply to. On the other hand, admission committees can benefit from the predictive model by using it as an additional tool to evaluate and prioritize candidates based on their predicted probabilities of admission.

To accomplish this goal, we will collect and analyze historical admission data from previous years, including factors such as undergraduate GPA, standardized test scores, letters of recommendation, personal statements, and any other relevant information available. By identifying patterns and correlations within this dataset, we will train a machine learning model to recognize the underlying relationships between applicant profiles and admission outcomes.

The predictive model will be designed to handle a wide range of data types, including numerical, categorical, and textual variables. To ensure its accuracy and reliability, we will employ state-of-the-art machine learning algorithms and techniques such as logistic regression, decision trees, random forests, or neural networks. The model will be trained and validated using appropriate evaluation metrics and cross-validation techniques to ensure its generalizability and robustness.

Additionally, we will incorporate feature engineering techniques to extract meaningful insights from the data and potentially identify hidden factors that strongly influence the admission decision process. This could include analyzing the importance of different features, identifying any biases or disparities in the admission process, and exploring ways to address them to ensure a fair and unbiased admission process.

By completing this project, we hope to contribute to the development of a transparent, data-driven, and efficient admission process for Master's programs. Our ultimate aim is to provide applicants with reliable predictions regarding their admission chances and support admission committees in their decision-making process
## Dataset
The Data Set Contains 8 columns and 400 rows. The Data Set Contains numerical and floating Data types.

The parameters included are :

GRE Scores ( out of 340 )

TOEFL Scores ( out of 120 )

University Rating ( out of 5 )

Statement of Purpose Strength ( out of 5 )

Letter of Recommendation Strength ( out of 5 )

Undergraduate GPA ( out of 10 )

Research Experience ( either 0 or 1 )
## Target
Chance of Admission
# Data Cleaning and Preprocessing
Columns in my dataset and their data types

<img width="292" alt="image" src="https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/assets/99163655/94e6f851-983c-431f-8a3c-4db60cc0fcd8">

The Description of my Dataset

<img width="553" alt="image" src="https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/assets/99163655/eafee749-1732-4ca4-b340-aeadecc66d06">
As there are no null values I went to visualization part to get some insights on my Dataset

# Data Visualization
I have creted a heatmap to visualize the correlation

![image](https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/assets/99163655/89355312-38c5-4da2-b449-e0cb182605d3)

As our Target value is Chance of Admission I also created a correlation matrix of chance of admission with other columns

![image](https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/assets/99163655/dc845253-b584-45d6-82b1-87ab94682cc2)

We can see from above that CGPA is the most correlated to chance of admit

# Prediction Models 

For this dataset I have decided to condered it as Regression problem and classification problem
The Regression models used in this are:
1) Linear Regression
2) Support Vector Regression
3) Random Forest Regressor
4) Gradient Boosting Regressor
The Clssification models used in this are:
1) Logistic Regression
2) Support Vector Machine
3) Kneighborsclassifier
4) RandomForestclassifier
5) GradientBoostingclassifier
I performed the models and got the following accuracy scores:

![image](https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/assets/99163655/855497a3-1ec4-406e-b29a-18bb2c3454c0)

![image](https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/assets/99163655/162fe7a1-b235-4495-a891-727921d844c8)

We can see from above that  'GradientBoostingclassifier' is the best model for prediction and the model is saved for prediction.
# Web Application Using Streamlit

In today's digital age, web applications have become essential tools for delivering content, providing services, and interacting with users. Streamlit, a powerful Python library, enables developers to quickly and easily create interactive web applications with minimal effort.

Here are some insights of web application 

<img width="1278" alt="image" src="https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/assets/99163655/3a83594f-c382-4af0-90e6-7df4d2207914">

<img width="971" alt="image" src="https://github.com/DATA-606-SPRING-2023-THU/SREEKANTH_REDDY_DATA690/assets/99163655/d451b2dd-f8ce-4dde-a15f-2ca2d75c0833">

# Conclusion:
The Masters Admission Prediction project has successfully achieved its objectives of developing a robust predictive model to estimate the likelihood of admission for future applicants to Masters programs. Through rigorous data collection, preprocessing, analysis, and model development, we have created a valuable tool that can provide insights and support decision-making for both applicants and admission committees.

 By leveraging machine learning techniques and historical admission data, we developed a predictive model that takes into account various factors such as undergraduate GPA, standardized test scores, recommendation letters, and personal statements.

Our model demonstrated promising results during evaluation, achieving high accuracy and performance metrics. It showcased its ability to generalize well and make accurate predictions for new applicants. The feature importance analysis revealed the key factors influencing admission outcomes, enabling applicants to identify areas of strength or areas for improvement in their profiles.


The deployment of the predictive model through a user-friendly interface or application provides applicants with valuable information about their chances of admission. It empowers them to make informed decisions about which programs to apply to, based on their predicted probabilities of admission. Admission committees can also benefit from the model by utilizing it as an additional tool to evaluate and prioritize candidates.

Overall, this project contributes to the field of Masters admission by leveraging data-driven methodologies to enhance the admission process. It provides a transparent and efficient tool that supports applicants in their decision-making and aids admission committees in their evaluation process. The project's outcomes can have a positive impact on the academic community by promoting fairness, objectivity, and informed decision-making in Masters program admissions.

Moving forward, the predictive model can be further improved and expanded. This could involve incorporating additional features, exploring different machine learning algorithms, or integrating real-time data updates to enhance accuracy and relevance. Continuous monitoring and evaluation of the model's performance can ensure its effectiveness and adaptability to changing admission trends and requirements.

In conclusion, the Masters Admission Prediction project has successfully achieved its objectives and demonstrated the value of predictive modeling in the admission process. The project's outcomes hold significant potential to improve the efficiency, fairness, and transparency of Masters program admissions, benefiting both applicants and educational institutions alike.
