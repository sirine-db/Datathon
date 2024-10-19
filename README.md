## 🎗Breast Cancer Detection

Breast Cancer Detection Using Machine Learning

<img src="https://cdn-images-1.medium.com/max/2600/1*gNcFEL1cpGpDC4vo1zUAWA.png" />

## 🎗 What is Breast Cancer?

Breast cancer is a disease in which abnormal breast cells grow out of control and form tumours. If left unchecked, the tumours can spread throughout the body and become fatal,
Early detection of breast cancer is crucial for improving survival rates, offering less aggressive treatments, and enhancing the quality of life.

##  💻 Role Of Machine Learning In Detection Of Breast Cancer

A mammogram is an x-ray picture of the breast. It can be used to check for breast cancer in women who have no signs or symptoms of the disease. It can also be used if you have a lump or other sign of breast cancer.

Screening mammography is the type of mammogram that checks you when you have no symptoms. It can help reduce the number of deaths from breast cancer among women ages 40 to 70. But it can also have drawbacks. Mammograms can sometimes find something that looks abnormal but isn't cancer. This leads to further testing and can cause you anxiety. 

Now while its difficult to figure out for physicians  by seeing only images of x-ray that weather the tumor is toxic or not training a machine learning model according to the identification of tumour can be of great help.

## Project Description

This script uses mammography data to predict whether a tumor is benign or malignant. After loading and cleaning the data(cell size, texture, and shape..), a correlation analysis is performed to remove less important features.                 
The dataset is then split into training and test sets.                 
Various machine learning models, including Kernel SVM, Naive Bayes, Logistic Regression, Random Forest Classification, and Nearest Neighbor, are trained on the training data, with a visualization of feature importance.                   
The models are then refined before making predictions on a separate test dataset.                
The results are exported to a CSV file, and the performance of the models is evaluated using accuracy and a confusion matrix.              
 
## 🗂️ Project Structure

The project is organized into the following directories:

- **data/**: Contains the dataset used for training and testing the models.
- **notebooks/**: Jupyter notebooks used for exploratory data analysis (EDA), model development, and evaluation.


## 📌RESULTS 
An accuracy of 96% was achieved by using  the models (kernel svm,Naive Bayes,Logistic Regression,Random Forest Classification,Nearest Neighbor)

## 👥 Contributors

Ines Djazari                   
Nait cherif Sabrinel              
Dob Serine                    
Laadi Meriem                 

##  📝Final Note 
This project was developed as part of a datathon organized by Micro Club. For more details, visit the following link: [https://microquest.microclub.info/challenges/671139aeaab8d87843b46963].

