<h1>Sentiments ON Apple In Tweeter </h1>
<h2>Introduction</h2>
Social media webweb sites like Twitter are essential stores for public perspectives and remarks withinside the virtual age. Improving product development, advertising and marketing plans, and client relationships for companies like Apple relies upon on their understanding of the way clients view their items on Twitter.

Understanding sentiment with the aid of using manually analyzing heaps of tweets, though, is a Herculean effort. Natural language processing (NLP) can automate this, letting businesses unexpectedly compare public opinion on a huge scale.

This mission objectives to create a NLP version that could robotically categorize a tweet`s sentiment as positive, negative, or neutral. This will allow Apple and different fascinated events to base their selections on public opinion, consequently guiding them. </br>

<h2>Business Understanding</h2>
Automating sentiment analysis on Twitter helps Apple and other interested parties to acquire insightful information without requiring great manual effort. Real-time tracking of public sentiment enables Apple to be more reactive to consumer input, maximize marketing strategies, and enhance product offers. In the end, this might result in more successful product launches and better consumer happiness.
<h2>Data Understanding</h2>
This project's dataset originates from CrowdFlower, through data.world. Over 3000 tweets manually rated for sentiment by human annotators make up the dataset. Every tweet is marked as either positive, negative, or neutral.

Source Summary: - Dataset: Apple Twitter Sentiment (CrowdFlower)
Source: data.world - Apple Twitter Sentiment
Given the task at hand, this dataset is quite useful since it directly addresses the need for an automated system to categorize public opinion on Twitter regarding Apple products. </br>

<h2>Data Preparation</h2>
Drop unnecessary columns
Goal: Remove unrelated columns used for analysis to make data records cleaner and more focused.
Reason:
Unrelated columns: These columns provide metadata or details that do not contribute to the mood analysis model. Delete data records and improve processing speed.
By removing columns like id, query, _unit_id, we focus only on important functions: tweet text and emotions. </br>

<h2>Exploratory Data Analysis (EDA)</h2>
<b>1. Which are the most dominating sentiments?</b>
<img src="https://github.com/BLACKSPI/Phase_4_project/blob/45745d0efe21023f899bd84617a19cdca72b2de1/Sentiment%20distribution.png", alt="sentiment distribution">

<p>This graph shows that most tweets are neutral about Apple. This indicates that the majority of users post factual or non-emotional content. Negative tweets are the second most common, highlighting a significant amount of criticism and complaints. Positive tweets are less common. This means that fewer users will express strong Apple approval. Very positive tweets are the least common and show that enthusiastic praise is relatively rare. Overall, the  distribution of mood suggests that  Apple receives a mix of opinions, but neutral arguments dominate more criticism than strong praise.</p>

