# Wikipedia Text Analysis and Classification Project

This project consists of three Jupyter notebooks focused on natural language processing, text representation, clustering, and classification. I built a dataset using the Wikipedia API, cleaned article titles and summaries, and compared multiple methods for analyzing topic structure in text. The project also includes a provided UCLA dataset of news article titles and topics for additional clustering and classification tasks.

## Project Goals
- Collect and organize text data from multiple topic areas
- Preprocess article titles and summaries for analysis
- Compare TF-IDF and embedding-based text representations
- Explore topic structure through similarity analysis and clustering
- Evaluate how well different methods classify documents by topic

## Methods Used
- Wikipedia API for data collection
- Text preprocessing with tokenization, stemming, and stopword removal
- TF-IDF and sentence embeddings for text vectorization
- Cosine similarity matrices and word clouds for topic exploration
- K-Means clustering for unsupervised grouping
- Random Forest for supervised topic classification
- Confusion matrices and classification metrics for evaluation

## Main Takeaway
This project showed a clear comparison in how different text methods perform. The analysis initially found that article summaries captured topic structure more clearly than titles, producing cleaner separation between groups and more accurate similarity-based clustering. As the project moved into clustering and classification, dense sentence embeddings consistently performed better than TF-IDF, especially when the goal was to capture semantic meaning rather than just word frequency. Ultimately, the results suggest that while TF-IDF is still useful for basic text representation, embedding-based methods gave stronger topic separation, higher classification accuracy, and a more reliable understanding of document meaning overall.

## Tools
Python, Pandas, NumPy, scikit-learn, NLTK, sentence-transformers, Matplotlib, WordCloud, Requests

## Notes
This project was developed for a UCLA course and was built as a text analysis and machine learning exercise centered on preprocessing text and comparing different ways to represent, group, and classify documents by topic.
