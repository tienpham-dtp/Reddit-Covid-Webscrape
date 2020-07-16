# Reddit-Covid-Webscrape
The reddit-webscraping.ipynb script will produce 3 tables for a subreddit thread: 
1) A subreddit's post table consists of all the posts information (id, title, url, body, date created)
2) A parent comments of each original post table consists of all the comments and replies to all the posts in all the posts
3) A relationshiptable consists of comment id and its parent's id (direct relationship to each comment - reply)

The COVID_textanalysis.ipynb script will include:
- text analysis with the use of Google's Universal Embeddings and Kmeans clustering to group title together based on semantic similarity
- apply LDA for topic modeling

