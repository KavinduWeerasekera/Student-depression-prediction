This project involves ML models to predict the student depression 🤖

Data was obtained from kaggle :https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset

We performed EDA on the dataset idenfied no missing values but we observed few outliers. But decided not to remove since they can have valuable information.

Next, we tuned 5 different classification models namely Random forest,XGBoost,logistic, SVM, decission trees fith robust tuning procedure with Grid search.

Tuning ➡️  Feature selection (RFECV) ➡️  Re tuning

SVM emerged as the optimal model with 84% test set accuracy📊

We build a website a so uses can intereact with our models capabilities and identify risk early. Web site include a dashboard, an AI agent who answers the questions based on the project report and form. 🧠💻
