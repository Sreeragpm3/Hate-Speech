# Hate-Speech-Recognition 
## What is Hate Speech detection?
Hate speech detection is the model which identifies and detects the hateful and offensive speech being poured on the internet. Social media is a place for many people to make hateful and offensive comments about others. So hate speech detection has become an important solution to problems in today’s online world.
## Steps in building Hate Speech detection using Machine Learning
### 1,Set up the development environment
The first major step is to set up the development environment for building a Hate Speech detection project with Python. For developing a Hate Speech detection project you should have the system with Jupyter notebook software installed

### 2,Understand the data
There are 7 columns in the hate speech detection dataset. They are index, count, hate_speech, offensive_language, neither, class and tweet. The description of the column is as follows.
#### index – This column has the index value
#### count– It has the number of users who coded each tweet
#### hate_speech – This column has the number of users who judged the tweet to be hate speech
#### offensive_language – It has the number of users who judged the tweet to be offensive
#### neither – This has the number of users who judged the tweet to be neither offensive nor non-offensive
#### class – it has a class label for the majority of the users, in which 0 denotes hate speech, 1 means offensive language and 2 denotes neither of them.
#### tweet – This column has the text tweet.

### 3,Import the required libraries
After analyzing the data our next step is to import the required libraries for our project. Some of the libraries we use in this project are pandas,numpy,scikit learn, and nltk.

### 4,Preprocess the data
In Data preprocessing, we prepare the raw data and make it suitable for a machine learning model. It is the first and crucial step while creating a machine learning model. When creating a machine learning project, it is not always a case that we come across clean and formatted data. And while doing any operation with data, it is mandatory to clean it and put it in a formatted way. So for this, we use the data preprocessing task.

### 5,Split the data
The next important step is to explore the dataset and divide the dataset into training and testing data.

### 6,Build the model
After segregating the data, our next work is to find a good algorithm suited for our model. We can use a Decision tree classifier for building the Hate Speech detection project. Decision Trees are a type of Supervised Machine Learning used mainly for classification problems.

### 7,Evaluate the results
The final step in machine learning model building is prediction. In this step, we can measure how well our model performs for the test input.

## Conclusion
we have built a project for Hate Speech detection using Machine Learning. Hate speech is one of the serious issues we see on social media platforms like Facebook and Twitter.

