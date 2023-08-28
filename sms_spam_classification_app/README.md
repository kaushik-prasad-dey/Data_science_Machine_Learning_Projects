# Streamlit dashboard
official website : https://streamlit.io/

# what is streamlit
Streamlit is an open-source app framework in python language. It helps us create beautiful web apps for data science and machine learning in a little time. 
It is compatible with major python libraries such as scikit-learn, keras, PyTorch, latex, numpy, pandas, matplotlib, etc.

#### SMS EMAIL SPAM Detector
##### Project description

A Natural Language Processing with SMS Data to predict whether the SMS is Spam/Ham with various ML Algorithms 
like MultiNomial Nayab Base, Gaussion Nayab Base, Bernoli Nayab Base, xgboost, DecisionTreeClassifier 
to compare accuracy and using various data cleaning and processing techniques like PorterStemmer,CountVectorizer with NLTK libraries.

The project has 4 main categories:
Data cleaning

Exploratory data analysis

Data Preprocessing

Building a classifier

Selecting the predictor algorithm for creating a live app using streamlit.

#### Exploratory data analysis 
##### showing pie chart for ham and spam distribution
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/167188f7-db48-4d0e-8d65-8bd4ba8194e4)

##### showing hist plot as per number of charecters count for target variable 0 and 1
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/4c3fd9e4-f46a-42d5-9ffb-bc23031fabb1)

##### showing hist plot as per number of words count for target variable 0 and 1
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/9b620624-c9de-48c9-85d9-afbeb3f0cf66)

##### showing pair plot as per num_charecters, num_words & num_sentences
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/df6eb75f-bd46-43a9-a5ca-05727e18278b)

##### showing co relation heatmap
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/5a2bd087-9bab-4879-b8e6-003ceed98765)

#### Data Pre-processing
LowerCase. Tokenization. Removing Special Charecter. Removing stop words and punctuation.

##### stop words
Stop words are a set of commonly used words in any language. 
For example, in English, “the”, “is” and “and”, would easily qualify as stop words. 
In NLP and text mining applications, stop words are used to eliminate unimportant words, 
allowing applications to focus on the important words instead.

##### using word cloud to understand the weight of transformed text
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/e572bf3e-f105-4b6f-bc27-5e0dc48492b2)

# virtual environment steps :
 python -m venv venv

 venv\Scripts\activate

 venv\Scripts\deactivate

 pip install -r requirements.txt

 streamlit run app.py

##### Inside the requirements.txt
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/1f98a107-32ff-499a-86ad-347523fcc35c)


# sample code :
import streamlit as st

import seaborn as sns

st.header("This is simple streamlit application")

st.text("step by step web app learning from creative soft")

df=sns.load_dataset('iris')

st.write(df.head(10))

#### alternatively, steps to be perfomed from pycharm:
  1) pip install streamlit
  2) pip install nltk
  3) python -m pip install scikit-learn
  4) python.exe -m pip install --upgrade pip
  5) python -m pip install -U scikit-learn
  6) pip3 freeze > requirements.txt
  7) streamlit run app.py

#### Example of test messages :
1) hi saw your presentation today.would you like to meet for a discussion. [output should be "NOT SPAM"]
2) congratulations you won 1000 call on this number to get your prize.
3) i am free today, let's go out for a movie.what do you say?
4) Did you see this match?it was insane.

# Streamlit Web App
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/4095fec1-9799-40c6-8dd9-eb761b209768)

## Heroku deployment process
1) https://id.heroku.com/login
   
##### Commands which is perfomred in pycharm side:
1) $ heroku login
2) $ git init
3) heroku git:remote -a spamsmscheckingapp
4) $ git add .
5) $ git commit -am "make it better"
6) $ git push heroku master

##### Heroku deployment screenshots
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/0e1905c5-643d-4945-af5c-e070f17b5fec)
![image](https://github.com/kaushik-prasad-dey/Data_science_Machine_Learning_Projects/assets/109330283/37f2ca58-8e1d-40b5-a5b8-022ff0c200f0)



