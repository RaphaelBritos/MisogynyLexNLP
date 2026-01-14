# MisogynyLexNLP
Overview

MisogynyLexNLP is a project that uses Natural Language Processing (NLP) and a custom misogyny term dictionary to detect and analyze misogynistic and misleading tweets related to women in politics. The project combines text preprocessing, manual labeling, social network analysis, and fact-checking data to map content dissemination patterns and identify influential users.

Features

Detect misogynistic content in tweets using a lexicon-based approach.

Identify misinformation by cross-referencing verified fact-checking sources.

Analyze social networks of users via retweets and replies.

Characterize user profiles and content propagation patterns.

Categorize tweets into types of misogyny and disinformation.

Methodology

Data Preprocessing

Clean and normalize tweets by removing links, emojis, hashtags, punctuation, numbers, stopwords, and extra spaces.

Convert all text to lowercase.

Filter tweets containing terms related to women in politics (e.g., “candidata”, “vereadora”, “prefeita”).

Social Network Analysis

Build interaction networks from retweets and replies.

Compute structural metrics such as centrality, density, and modularity.

Identify influential users in content dissemination.

Misogyny Detection

Apply NLP techniques to search for dictionary terms in tweets.

Manually validate detected misogynistic content.

Categorize tweets into: political gender violence, digital misogyny campaigns, stereotype mobilization, type of violence, and digital elements.

Misinformation Detection

Extract key terms from posts verified by fact-checking agencies (Lupa, Estadão Verifica, Fatos ou Fakes, Aos Fatos).

Match tweets against verified content and label as misinformation, not misinformation, or unclassified (-1).

Map propagation patterns via engagement, retweets, and user centrality.

Data

Source: Tweets from Brazilian cities (São Paulo, Recife, Porto Alegre) filtered for female political figures.

Size: 23,713 tweets.

Fact-checking references from official verification agencies.

Technologies

Python

NLTK / spaCy – text preprocessing and NLP

NetworkX / iGraph – social network analysis

Pandas / NumPy – data handling

Matplotlib / Seaborn – visualization
