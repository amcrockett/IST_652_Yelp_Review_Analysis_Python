# IST_652_Yelp_Review_Analysis_Python
We have chosen to conduct analysis on the public dataset provided by Yelp.

Topic, Assessment, Scope
We have chosen to conduct analysis on the public dataset provided by Yelp. This dataset was
provided as one of their Natural Language Processing & Sentiment Analysis challenges. The
Yelp dataset is big data with nearly 6 million reviews. The main focus is assessing what
comprises a review. Can we extract positive or negative sentiment based on the data provided?
Can we match the positive and negative sentiments to star ratings given by the Yelp Reviewers?
 The business dataset contains the following pieces of information:
    ● Business ID
    ● Name
    ● Neighborhood
    ● Address/City/State/Postal/Lat/Long
    ● Stars
    ● Review Count
    ● Is Open
    ● Attributes (such as takeout, parking, etc.)
    ● Categories (such as Mexican, Burgers, Gastropub, etc.)
    ● Hours of operation
Cross referencing the business ID, the review dataset contains the following:
  ● Review, User, and Business IDs
  ● Stars
  ● Date given
  ● Text (free form, the review itself)
  ● Useful, Funny, Cool binary flags
There is also user data provided as well, but we will probably not be using this dataset.
Methods of Analysis
  ● Data Extraction - the dataset is being given as JSON format, so we will need to extract,
  manipulate, and clean the data as necessary.
  ● Data Structure - we will be using pandas dataframes to structure the data for analysis.
  ● Visualization - although visuals are not mandatory, we plan to explore the data visually
  with plotly and matplotlib, such as word and bigram frequency comparisons.
  ● Unstructured Data - we will be using methods of analysis on unstructured data such as
  text tokenization, regular expressions, finding patterns in text, and sentiment analysis.
  We also hope to incorporate material from unit 10 (social network analysis and facebook
  post comments) to use on analyzing yelp reviews.
