**Project 1: NLP Sentiment Analysis**


This project focuses on performing sentiment analysis using Natural Language Processing (NLP) techniques. It utilizes both VADER Sentiment Analysis and RoBERTa Pretrained Model to analyze the sentiment of textual reviews.


**Overview**


The project is designed to demonstrate how to:
1.Perform sentiment analysis on textual data using VADER Sentiment Analyzer and RoBERTa Pretrained Model.

2.Visualize sentiment analysis results using bar plots and pair plots.

3.Utilize NLTK for text preprocessing tasks such as tokenization, POS tagging, and chunking.

4.VADER Sentiment Analysis: Using the VADER lexicon-based model to analyze sentiment in the reviews.

5.RoBERTa Model: Utilizing a pretrained RoBERTa model for more nuanced sentiment analysis.


**Setup Instructions**

1.Clone the repository: Clone this GitHub repository to your local machine.
     
     git clone https://github.com/your_username/project1.git

2.Install dependencies: Navigate to the project directory and install the required libraries using pip.

      cd project1
      pip install -r requirements.txt

3.Download NLTK resources: Run the following commands in Python to download necessary NLTK resources.

      import nltk
      nltk.download('punkt')
      nltk.download('averaged_perceptron_tagger')
      nltk.download('maxent_ne_chunker')
      nltk.download('words')
      nltk.download('vader_lexicon')

4.Run the code: Execute the main Python script project1.ipynb or project1.py to see the sentiment analysis results and visualizations.

      python project1.py



