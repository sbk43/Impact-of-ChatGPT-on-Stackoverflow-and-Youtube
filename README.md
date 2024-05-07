# Impact-of-ChatGPT-on-Stackoverflow-and-Youtube
Impact of ChatGPT on Stackoverflow and Youtube Engagement

The purpose of this project is to assess the impact of ChatGPT launch on platforms like stackoverflow and youtube. 

Stackoverflow:

Stackoverflow is a platform which created an environment for asking and answering questions related to coding. Launch of ChatGPT must be having a significant impact on its engagement. In this project we want to assess its impact and quantify it. We did an extensive EDA on the stackoverflow questions and utilized regression discontinuity as a natural experiment to find the causal effect.

Data Collection: 
Data is obtained using questions endpoint of stackexchange API. There is a maximum limit of 10000 requests to this API. Each request can give a maximum questions of 100. We used requests package of python to extract the data. The script to extract the data in csv format can be found in Data Pull folder. Since the file size is >25 MB, we uploaded it in Data folder by splitting it into several smaller files. For this analysis, we only considered questions related to python and java as they are widely used. As the ChatGPT launch date is Nov 30, 2022, we considered data 12 months before and after the launch of ChatGPT i.e, Nov'21 to Dec'23.

Stackoverflow Engagement metrics:
1. Number of Questions
2. Average Answers per question

Results:
On an average, there were 20000 questions related to python on stackoverflow before the launch of ChatGPT. There is a causal reduction of -2900 questions, which is 14.5% reduction. We did not find any statistically significant reduction for questions related to java. There is no impact on Average answers per question for both python and Java.


YouTube:

In order to supplement our analysis on Stack Overflow, we decided to explore, at an elementary level, if the launch of ChatGPT is associated with any change in the patterns of content creation on YouTube and if yes, is viewer interaction on content also changing in terms of scale. 

Data Collection:
Data is obtained using search and coomentsthread endpoints of YouTube API. Just like Stackoverflow, the script to extract the data in csv format can be found in Data Pull folder. Since the file size is >25 MB, we uploaded it in Data folder by splitting it into several smaller files. For the analysis, we considered below channels as they talk about AI.
1. DeepLearningAI​
2. Lex Fridman​
3. Sentdex​
4. StarQuest with Josh Starmer​
5. Two Minute Paper
   
We extracted metrics such as video title, video published date, likes, comments, comment date, etc for all the videos present in these channels.

Results:
We segregated these videos into AI and non-AI videos based on the title. After ChatGPT launch, there is more enagement on AI related videos in terms of comments. For some channels, views are higher as well



