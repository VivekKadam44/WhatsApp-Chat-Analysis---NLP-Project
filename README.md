# WhatsApp-Chat-Analysis-NLP-Project
## Introduction

A data science project that utilizes natural language processing (NLP) techniques to analyze WhatsApp chat data. The objective is to extract insights, patterns, and trends from the conversations.

## Features

- Data preprocessing: Clean and transform raw chat data into a suitable format for analysis.
- Sentiment analysis: Determine the sentiment (positive, negative, neutral) of chat messages.
- Word frequency analysis: Identify the most frequently used words or phrases in the chats.
- Topic modeling: Extract topics or themes using techniques like Latent Dirichlet Allocation (LDA).
- Visualizations: Generate visual representations of the analysis results.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Requirements

- Python 3.x
- Jupyter Notebook or any Python IDE
- Libraries:
  - pandas
  - numpy
  - nltk
  - matplotlib
  - seaborn
  - many more......

## Installation

pip install -r requirements.txt

## Usage
-Place your WhatsApp chat export file (chat.txt or chat.csv) in the project directory.\
-Open the Jupyter Notebook or Python IDE.\
-Open the whatsapp_chat_analysis.ipynb notebook.\
-Modify the file path in the notebook to point to your chat data file.\
-Run the notebook cell by cell to perform the analysis.\
-Explore the results, visualizations, and insights obtained from the chat data.

## Note
There are some errors in the code lines of the "Sentiment-based Word Cloud" section. The code is not able to detect any positive or negative words from the word clouds. This issue can also be observed in the previous codes, as no positive or negative words were detected in the dataset.\
In the "Picture Analysis" section, no images were exchanged in the chat data. Therefore, the specified path is a dummy path, resulting in the "colors.pkl" file not being created. This is the reason for the displayed error.
