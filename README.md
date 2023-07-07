# Multi Modal Machine Learning Projects
This repository features three machine learning projects that leverage the power of machine learning to analyze sensory, visual, and audio data. Throughout these projects, I explored the application of various libraries such as PyTorch, Keras, and particularly Pandas, to tackle challenging tasks like emotion recognition and sentiment analysis. The results of these projects are consistently improving as further advancements are made.

## Machine_LearningData_Analysis Project

The Machine_LearningData_Analysis project focuses on utilizing the Pandas DataFrame to process substantial amounts of article and author data. By leveraging the capabilities of Pandas, we can create dataframes and graphs for analysis. The project involves breaking down author publications by year and area, enabling us to generate graphs that illustrate the occurrences of publications worldwide.

  ### Skills and Packages Used
  Languages:
  - Python

  Packages:
  - Pandas
  - Scikit-learn (Sklearn)
  - MatPlotLib

## Sentiment_Data_Analysis_Machine_Learning Project
The Sentiment_Data_Analysis_Machine_Learning Project focuses on utilizing machine learning techniques to develop a model that can understand the sentiment of tweets. In this project, a carefully curated dataset is used, where each tweet is assigned a sentiment score ranging from 0 to 1. By leveraging natural language processing techniques, the project aims to analyze the connotations and sentiments expressed in the tweets to shed valuable insights in a plethora of fields.

### Project Workflow
- Data Cleaning: The first step involves cleaning the tweet data by removing unnecessary characters, URLs, and other noise. This ensures that the data is in a standardized format for further processing.

- Feature Extraction: Next, the project focuses on extracting relevant features from the cleaned tweets. Techniques such as Bag of Words and Term Frequency-Inverse Document Frequency (TFIDF) are commonly employed to represent the textual data in a numerical format.

- Machine Learning Model Training: Once the features are extracted, various machine learning models are employed to train on the labeled sentiment dataset. In this project, specifically, models like Logistic Regression and Naive Bayes are used to develop a predictive model that can classify the sentiment of new tweets.

### Skills and Packages Used
Languages:
  - Python

  Packages:
  - Pandas
  - Scikit-learn (Sklearn)
  - MatPlotLib

  Models (Used on Bag of Words and TFIDF features):
  - Logistic Regression
  - Naive Bayes

## Detecting_Emotion_Through_Audio Project
The Detecting_Emotion_Through_Audio project aims to utilize machine learning techniques to analyze short audio clips and determine the underlying emotion expressed in the audio. The project focuses on leveraging a carefully curated dataset consisting of audio files categorized into emotions such as anger, sadness, happiness, and fear. By extracting relevant features, including factors like timbre and pitch, the project aims to develop a model capable of accurately identifying the emotions present in the audio clips.

### Project Workflow
- Data Collection: Curated a diverse dataset of labeled audio clips representing different emotions

- Preprocessing: Prepared the audio data by standardizing formats and performing necessary cleaning and noise removal

- Feature Extraction: Extracted relevant audio features like loudness, timbre, chroma, and spectral characteristics

- Data Split: Divided the dataset into training and testing sets

- Model Selection and Training: Chose and trained appropriate machine learning models

- Model Evaluation: Evaluate the model's performance using metrics like accuracy, precision, recall, and F1 score

- Testing and Performance Evaluation: Assess the model's performance on unseen audio clips using the testing set

### Skills and Packages Used
Languages:
  - Python

  Packages:
  - Librosa
  - TensorFlow
  - Scikit-learn (Sklearn)
  - MatPlotLib

  Models:
  - Random Forrest
  - SVC
