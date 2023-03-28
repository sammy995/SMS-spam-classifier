## SMS Spam Classifier #

This project aims to classify whether an SMS message is spam or not. The project is built using Python and several libraries such as pandas, numpy, matplotlib, seaborn, nltk, and sklearn.

The project consists of the following steps:

### Data Cleaning  
  The first step is to clean the data by dropping unnecessary columns and renaming the remaining ones.

### EDA: 
  Exploratory data analysis is performed to understand the dataset and its characteristics.

### Text Pre-processing: 
  The text data is pre-processed to remove stop words, punctuation, and perform stemming.

### Model building: 
  The Random Forest algorithm is used to build a classification model.

### Evaluation: 
  The performance of the model is evaluated using accuracy, precision, and confusion matrix.

### Improvement: 
  Further improvements can be made by trying out other algorithms, hyperparameter tuning, and using other text pre-processing techniques.

### Application Interface: 
  A user interface can be created to take an input message and classify it as spam or ham.

### Deployment: 
  The model can be deployed using cloud platforms like AWS or Google Cloud.

## Installation
To run this project, you need to have Python installed on your system. You can install the required libraries using the following command:

``` pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud streamlit ```

### Usage
  The project is implemented in a Jupyter Notebook file named SMS_Spam_Classifier.ipynb. To run the application:

```streamlit run app.py```

You will see a text area where you can enter the SMS or email message. Click on the "Predict" button to see whether the message is spam or not.

### How it Works
The application works in the following way:

1. The input message is preprocessed using the transform_text function. This function converts the text to lowercase, tokenizes it, removes punctuation and stop words, and performs stemming.
2. The preprocessed message is then vectorized using the TF-IDF vectorizer.
3. The model predicts whether the message is spam or not.
4. The result is displayed on the screen.

### Files
The following files are used in this application:

1. app.py: The main application file.
2. vectorizer.pkl: The saved TF-IDF vectorizer.
3. model.pkl: The saved model.

### Dataset
  The dataset used in this project is the "SMS Spam Collection" dataset available on Kaggle. The dataset consists of 5,572 SMS messages, out of which 4,827 are ham and 747 are spam.

### License
  This project is licensed under the MIT License. You are free to use, modify, and distribute the code as per your requirement.
