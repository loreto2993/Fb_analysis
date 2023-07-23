# Fb_analysis
This article is a Facebook sentiment analysis using Vader, nowadays many government institutions and companies need to know their customers’ feedback and comment on social media such as Facebook.

What is sentiment analysis?
Sentiment analysis is one of the best modern branches of machine learning, which is mainly used to analyze the data in order to know one’s own idea, nowadays it is used by many companies to their own feedback from customers.

Sentiment analysis is a valuable tool in various fields because it allows us to gain insights from large amounts of textual data by determining the emotional tone and subjective opinions expressed in the text. Here are some reasons why we should use sentiment analysis:

Understanding customer opinions: Businesses can use sentiment analysis to gauge customer sentiment towards their products, services, or brand. This helps them identify areas of improvement and make data-driven decisions to enhance customer satisfaction.

Market research: Sentiment analysis can be used in market research to analyze public opinions about specific products, industry trends, or competitors. This information can be crucial for companies when devising marketing strategies or launching new products.

Social media monitoring: Sentiment analysis is widely used in social media monitoring to track how people feel about specific topics, events, or brands. This enables companies and organizations to respond promptly to customer concerns or emerging issues.

Crisis management: During a crisis or a public relations issue, sentiment analysis can help organizations assess the sentiment of the public and manage the situation accordingly.

Political analysis: Sentiment analysis can be applied to political discussions, helping politicians and policymakers understand the public's sentiment towards particular policies or political figures.

Installations in Anaconda
NLTK:is used for understanding of human natural language. 
Installation Using conda command.
 
conda install -c anaconda nltk
Installation Using pip.
pip install nltk
NumPy: is a python package used for scientific and computional methods in python. 
Installation Using conda.
conda install -c conda-forge numpy
Using pip.
pip install numpy
Pandas: is a python module used for data preprocessing and analysis . 
Installation Using conda
conda install -c anaconda pandas
Installation Using pip.
pip install pandas
Matplotlib: is a python module used for data visualization and and 2D plotting for representation of data. 
Installation Using conda.
conda install -c conda-forge matplotlib
Installation Using pip.
pip install matplotlib 


Authentication
There are many ways to fetch Facebook comments those are: 

Facebook graph API
Direct download from Facebook
Downloading from another dataset provider sites

We follow these major steps in our program: 

Downloading(fetching) facebook comment from Kaggle site and save it as text format.
Preprocessing the data through SkLearn and nltk libraries .we first tokenize the data and then after tokenizing we stemize and lemmatize.
Parse the comments using Vader library . Classify each comment as positive, negative or neutral. 
