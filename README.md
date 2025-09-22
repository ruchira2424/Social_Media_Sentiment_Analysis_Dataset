# Social Media Sentiment Analysis Dataset

## Overview
This repository contains a Jupyter Notebook (`Task9.ipynb`) and a dataset (`3) Sentiment dataset.csv`) for analyzing social media posts with sentiment labels. The dataset includes social media posts from platforms like Twitter, Instagram, and Facebook, along with metadata such as sentiment, timestamps, user information, hashtags, retweets, likes, country, and more.

The Jupyter Notebook provides initial exploration of the dataset using Python libraries (`pandas` and `numpy`) to load and display the data.

## Dataset Description
The dataset (`3) Sentiment dataset.csv`) contains the following columns:
- **Unnamed: 0.1, Unnamed: 0**: Index columns (likely from data export).
- **Text**: The content of the social media post.
- **Sentiment**: Sentiment label (e.g., Positive, Negative, Neutral, Happy).
- **Timestamp**: Date and time of the post.
- **User**: Username or identifier of the poster.
- **Platform**: Social media platform (e.g., Twitter, Instagram, Facebook).
- **Hashtags**: Hashtags associated with the post.
- **Retweets**: Number of retweets for the post.
- **Likes**: Number of likes for the post.
- **Country**: Country of origin for the post.
- **Year, Month, Day, Hour**: Extracted components of the timestamp.

The dataset includes posts from various years (e.g., 2015–2023) and covers activities such as daily experiences, hobbies, school events, and more, with a focus on high school-related posts in the later entries.

## Files
- **Task9.ipynb**: Jupyter Notebook containing Python code to load and preview the dataset using `pandas`. It displays the first 20 and last 20 rows of the dataset.
- **3) Sentiment dataset.csv**: The raw dataset in CSV format.

## Prerequisites
To run the notebook, you need the following Python libraries:
- `pandas`
- `numpy`

You can install them using pip:

pip install pandas numpy

#!/bin/bash
# Clone the repository
git clone https://github.com/your-username/social-media-sentiment-analysis.git

# Navigate to the repository folder
cd social-media-sentiment-analysis
