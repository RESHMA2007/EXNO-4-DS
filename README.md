# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
![Screenshot 2025-04-19 133830](https://github.com/user-attachments/assets/6f1c8913-77e5-4492-8d10-28638c18266d)
![Screenshot 2025-04-19 133844](https://github.com/user-attachments/assets/6cc39292-1a59-4ee8-af4f-247e28a9ec52)
![Screenshot 2025-04-19 133854](https://github.com/user-attachments/assets/7a0c9aee-23f5-4dfe-8282-b3b1c722714f)
![Screenshot 2025-04-19 133910](https://github.com/user-attachments/assets/9ae0a7b6-dda0-4d87-b31b-d9b126d3c0b3)
![Screenshot 2025-04-19 133921](https://github.com/user-attachments/assets/6d197126-d40a-405b-82d4-3c9bfbf6c6ce)
![Screenshot 2025-04-19 133936](https://github.com/user-attachments/assets/fdae3445-3e97-480e-9e62-c3dc1b299c07)
![Screenshot 2025-04-19 133950](https://github.com/user-attachments/assets/fa5f44ea-8425-4782-9bc6-83cd4af5acbb)
ROBUST SCALER
![Screenshot 2025-04-19 134000](https://github.com/user-attachments/assets/653edd47-457b-4d58-b879-47a8084dde1b)

# RESULT:
The Feature Scaling process and Feature selection process is successfully completed.
