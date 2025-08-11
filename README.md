# brand-mapping-and-customer-segmentation-of-major-indian-airlines
# Objective
For a service-based company, customers are the key factor. To understand customer perspectives, brand positioning has been done based on them. Using this, we can identify what needs improvement and what is already good in a particular airline.

# Dataset Description
The data has been scraped from the www.airlinequality.com website using the BeautifulSoup and Requests packages.

# Airlines Analyzed
Air India, Air Asia India (referred to simply as Air Asia in our context), Akasa Air, Alliance Air, Air India Express, GoAir, GoFirst, Indigo, SpiceJet, and Vistara.

# Data Preprocessing
* Sentence tokenization
* Punctuation removal
* Word tokenization
* Lemmatization
* Stopword removal (retaining "but", "not" and "very")
* Bag of Words

# Sentiment Analysis
The sentiment analysis has been carried out by categorizing the reviews into 10 topics:
* Flight Booking
* Staff Service
* Fare
* Food
* Time Management
* Cleanliness
* Customer Service
* Flight Features
* Special Assistance
* Seat Comfort
A lexicon-based approach (VADER) was used for sentiment analysis.

# PCA and Factor Biplot
PCA Biplot and Factor Biplot were used for brand positioning and to understand the strengths and weaknesses of each airline.

# Limitation
Several airlines have since been merged, which is the primary limitation of this project.
