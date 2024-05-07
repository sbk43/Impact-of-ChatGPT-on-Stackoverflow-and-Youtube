# IMPACT OF ChatGPT ON DIGITAL ENGAGEMENT: A STUDY ON STACKOVERFLOW AND YOUTUBE

## Overview

This repository contains all the materials related to our project aimed at understanding the impact of the AI model ChatGPT on digital engagement, specifically on Stack Overflow and YouTube. Our study explores shifts in engagement patterns, question similarity on Stack Overflow, and changes in video content and viewer interactions on YouTube. Our results are detailed out in this blog post: https://open.substack.com/pub/tarikajain/p/the-ai-disruption-chatgpts-takeover?r=2viqfw&utm_campaign=post&utm_medium=web&showWelcomeOnShare=true

### Project Title
IMPACT OF ChatGPT ON DIGITAL ENGAGEMENT: A STUDY ON STACKOVERFLOW AND YOUTUBE

### Purpose
As AI reshapes numerous aspects of our digital interactions, we investigate how ChatGPT, one of the most sophisticated AI models developed by OpenAI, affects user behavior on prominent platforms. Our goal is to uncover and quantify these changes, providing insights into how artificial intelligence is transforming the landscape of online content and community interactions.

### About ChatGPT
ChatGPT is a variant of the GPT (Generative Pre-trained Transformer) models, known for generating human-like text based on the prompts it receives. Its capabilities include answering questions, generating explanatory text, and even writing code.

### About StackOverflow
Stack Overflow is a pivotal resource for developers worldwide, offering a platform to ask questions and share knowledge about programming. Its community-driven approach has made it an essential tool for coding professionals.

### About YouTube
YouTube stands as a global platform for video sharing where users upload and interact with content. It serves as a significant source of information and entertainment for diverse audiences.

### Hypotheses
- **Hypothesis-1:** The engagement levels on Stack Overflow have reduced because of the launch of ChatGPT.
- **Hypothesis-2:** After the launch of ChatGPT, Stack Overflow will see dissimilar questions compared to prior questions.
- **Hypothesis-3:** ChatGPT has affected content creation and engagement on YouTube.

### Data Source
Data was collected through the Stack Exchange API and YouTube API. These platforms provide extensive access to historical data, which we utilized to perform our analyses.

## Repository Structure

### Data Pull (folder)
Contains two Jupyter notebooks:
- `YouTube Data Pull.ipynb`: Scripts used to fetch video and comments data from YouTube.
- `Stackoverflow Data Pull.ipynb`: Scripts used to fetch question data from Stack Overflow.

### Data (folder)
This folder contains multiple CSV files split due to GitHub's file size restrictions:
- `stackoverflow 1.csv` to `stackoverflow 27.csv`: Data on questions tagged with Java and Python, including publication date and answer count.
- `all_video_comments 1.csv` to `all_video_comments 6.csv`: Comments data from YouTube videos.
- `youtube_channel_videos_details.csv`: Contains details from 5 YouTube channels including channel id, video id, title, description, like count, view count, and comment count.

### Analysis Code (folder)
This folder includes notebooks and R Markdown files used for detailed data analysis:
- `Merge_csv_files.ipynb`: A notebook for merging split data files.
- `Stackoverflow Analysis.ipynb`: Contains exploratory data analysis, regression discontinuity analysis, and cosine similarity analysis for Stack Overflow data.
- `youtube_eda.Rmd` and `youtube_eda.html`: Exploratory data analysis of YouTube data.
- `sentiment_youtube_comments.Rmd` and `sentiment_youtube_comments.html`: Sentiment analysis on YouTube comments.

### Results
Our analysis indicated significant changes in engagement and content interaction on both Stack Overflow and YouTube, attributed to the integration and influence of ChatGPT.
