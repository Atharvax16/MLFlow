# MLFlow
Understanding the experimentation of Machine Learning models and Hyper Parameters Tuning
<img width="761" height="662" alt="image" src="https://github.com/user-attachments/assets/91d0d10d-3c67-41ab-a3fc-4bb278dedfc0" />


1.)from sklearn.compose import ColumnTransformer
-->Many datsets contains features of diffrent types ,text,floats and dates where each type of feature requires seprate preprocessing or feature extaraction steps.
Often it is easiest to preprocess data before applying scikit-learn methods

What columntransformer does is --> helps performing doffrent transformation for different columns of the data within a Pipeline that is safe from data leakage and that can be parametrized.

It works on arrays,sparse amtrices and pandas dataframe
