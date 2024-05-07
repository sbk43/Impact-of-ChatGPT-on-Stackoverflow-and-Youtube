# Impact-of-ChatGPT-on-Stackoverflow-and-Youtube
Impact of ChatGPT on Stackoverflow and Youtube Engagement

The purpose of this project is to assess the impact of ChatGPT launch on platforms like stackoverflow and youtube. 

Stackoverflow:

Stackoverflow is a platform which created an environment for asking and answering questions related to coding. Launch of ChatGPT must be having a significant impact on its engagement. In this project we want to assess its impact and quantify it. We did an extensive EDA on the stackoverflow questions and utilized regression discontinuity as a natural experiment to find the causal effect.

Data Collection: 
Data is obtained using questions endpoint of stackexchange API. There is a maximum limit of 10000 requests to this API. Each request can give a maximum questions of 100. We used requests package of python to extract the data. 

