# capstone_greenworkforce

Researcher: lucy.adeniji@lis.ac.uk

## GWX Data Source

The Green Jobseekers Dataset, owned by Greenworkx, a climate tech start-up focused on building and upskilling the green workforce, serves as the foundation for the initial quantitative analysis. The dataset contains information on over 10,000 potential new entrants who have expressed interest in green careers, including their location, education, gender, and age. By analyzing this anonymized data and identifying recurring themes in the 'interest in green career' field, I aim to quantitatively assess the demographics of the UK's green workforce. 


## Analyzing Social Media Data: Public Career Advice Subreddits  

To gain a deeper understanding of the perceptions and attitudes towards skilled technical trades and blue-collar careers among potential entrants to the green workforce, I employ a mixed-methods approach, combining natural language processing (NLP) and thematic analysis (Creswell & Plano Clark, 2017). The data source for this research is the Reddit social media platform, which boasts approximately 430 million users, with 6.3 million in the UK (Reddit, 2021). Three main career advice subreddits (r/careerguidance, r/career_advice, and r/findapath) were selected to create a diverse, non-biased dataset. Using the PRAW Reddit API Wrapper, approximately 10,000 posts and comments were collected on June 10, 2024. 

Data preprocessing involved combining each subreddit into a centralized database, resulting in a finalized dataset of 10,240 posts and comments written by 8,281 unique authors/users, with 1,048 posting multiple times. The data was then cleaned, tokenized, lemmatized, and stopwords were removed in preparation for analysis. 

## Natural Language Processing of Reddit Data

The first stage of analysis employs TF-IDF (Term Frequency-Inverse Document Frequency) to identify the most important and relevant terms or phrases related to discussions about skilled trade career routes. This technique highlights terms that are frequently mentioned in Reddit posts or comments but are relatively rare across the entire corpus, providing insight into the key topics and concepts discussed in the context of skilled trades. 

The second stage involves VAD (Valence-Arousal-Dominance) analysis, which measures the emotional dimensions of text data. Valence represents the positive or negative sentiment, arousal indicates the level of excitement or intensity, and dominance reflects the degree of control or power expressed. VAD analysis is conducted on the key terms identified through TF-IDF to gain insights into the emotional aspects and sentiments surrounding the discussions related to skilled trade career routes. 

Following the TF-IDF and VAD analyses, which identified significant keywords and conversations within the corpus, a more focused subsection was selected for targeted thematic analysis.
