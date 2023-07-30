# An Analysis of Menstruation-related Tweets since 2006

Social media platforms, especially twitter shine a light into current perceptions and popular opinions. The societal taboos and lack of open dialogue surrounding menstruation contribute to myths, misconceptions, and limited awareness. Through this project, we analyze twitter conversations to address the following questions:

- What are the prevailing sentiments and emotions expressed in menstruation-related tweets?
- What are the key topics, themes, and subtopics that emerge from the Twitter discussions?
- How can data-driven analysis help debunk myths, promote education, and facilitate positive conversations about menstruation?

## Methodology
### Twitter Extraction
The first step of analyzing twitter data is to collect the twitter data. For this particular project, we chose to use the Snscrape package to extract tweets. A popular alternative often used to extract tweets is the Tweepy package. While both packages have their pros and cons, in this instance Snscrape’s ability to collect tweets further back than a week was of utmost importance. We searched tweets with a list of keywords relating to menstruation in a date frame from the inception of twitter to March 2023.

### Pre-Processing
Once collected, the tweets underwent several preprocessing steps to clean the text and ensure its suitability for analysis. This involved removing special characters, URLs, and hashtags, as well as tokenizing the text by splitting it into individual words. We also eliminated common stop words and applied lemmatization to standardize the words. These preprocessing techniques helped us eliminate noise, reduce dimensionality, and enhance the semantic representation of the text.

### Exploratory Data Analysis
To take a first glance at the data we used a couple strategies to investigate. We first took note of the most popular accounts mentioned and hashtags noted. We then looked at the most popular bigrams and trigrams of tweets. This allowed us to uncover unique patterns and gain deeper insights into the language used in twitter conversations about menstruation.

### Topic Modeling
For the fun part – discovering and grouping what key topics arose in the tweets, we used the Short Text Topic Modeling (STTM) algorithm. STTM is specifically designed to handle short, noisy texts like tweets. By applying this algorithm, we identified distinct clusters of related tweets, enabling us to uncover the prominent topics and subtopics present in the data.

### Sentiment Analysis
With tweets now grouped by topic, we wanted to see the sentiments around each cluster. We employed the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool to analyze tweets. VADER provides a pre-trained sentiment lexicon specifically designed for social media texts. By analyzing the polarity and intensity of sentiment in the tweets, we gained valuable insights into the emotional tones associated with menstruation-related discussions.

## Future Considerations
This project uncovered such valuable insights into the conversations around menstruation, so its only natural to think about how much deeper we can go into the subject. Below are some ideas for future related research.

- Topic Evolution: Track the evolution of topics and themes related to menstruation over time. Analyze emerging trends, significant events, or changes in public perception. Compare the discourse in different time periods to identify shifts and progress in the menstrual health domain
- Geospatial Analysis: Explore the geographic distribution of tweets related to menstruation. Analyze regional variations, cultural influences, and disparities in the discussions
- User Segmentation: Segment Twitter users based on their profiles, demographics, or tweet content to understand the different perspectives, experiences, and attitudes towards menstruation
- Social Network Analysis: Investigate the social connections and interactions between users discussing menstruation on Twitter. Analyze network structures, identify influential users, and explore the dynamics of information dissemination
