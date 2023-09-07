# Extractive_Text_Summariser
An extractive text summarizer is a tool designed to condense lengthy documents or articles by selecting and extracting the most important sentences or phrases while retaining the original context. It identifies key sentences that encapsulate the main ideas and essential information from the source text. Unlike abstractive summarizers, which generate new sentences, extractive summarizers rely on the existing content. This technology is widely used to help users quickly grasp the key points of a document, making it a valuable tool for researchers, journalists, and anyone seeking to efficiently digest large volumes of text. I have implemented and developed this system using generated word vectors, using the skip-gram model and page rank algorithm. The approach used here is unsupervised in nature giving us the freedom that no pretrained word vectors are being used here, and our model extracts information from the given text and gives the summary. A dense network with one hidden layer is used. The code is developed in Keras.
### Skip Gram Model
The skip-gram model is a popular natural language processing (NLP) technique used for word embedding, a process that represents words as dense vectors in a continuous vector space. Introduced as part of the Word2Vec framework, skip-gram is designed to predict context words (words that appear nearby) given a target word. It works by training a neural network to maximize the likelihood of predicting context words based on the target word. By doing so, it learns to capture semantic relationships between words, encoding them as vectors that capture meaning and similarity. Skip-gram has proven to be highly effective at capturing semantic information from large text corpora and has found widespread use in various NLP tasks, including machine translation, sentiment analysis, and document retrieval. It's a crucial component in modern NLP models and has significantly improved our ability to process and understand human language in the digital age. We use this to get the probabilities of the words falling neighboring to one another which will be used to find the word vectors
### Page Rank Algorithm
The PageRank algorithm, developed by Larry Page and Sergey Brin, co-founders of Google, is a fundamental component of search engine technology. It revolutionized the way search engines rank web pages by assessing their importance based on a network of hyperlinks. PageRank works on the principle that a web page's significance can be determined by the number and quality of links pointing to it. In essence, it views the web as a vast interconnected graph, where each web page is a node, and hyperlinks represent edges. Pages with more incoming links from reputable sources are considered more authoritative and, therefore, rank higher in search results. PageRank has played a pivotal role in improving the relevance and quality of search engine results, making it an integral part of the modern internet landscape. While it's no longer the sole factor in ranking, it laid the foundation for sophisticated algorithms used by search engines today.

<p align="center">
<img src="folder_for_data/page rank.png" alt="seg" " title="Page Rank Algorithm"/>


<p>


​



