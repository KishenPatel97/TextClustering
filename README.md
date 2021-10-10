# CSCE 5290: Natural Language Processing Project Proposal

## Team Members:
Kishen Patel\
R. Cooper Snyder\
Miguel Quintana

### Project Description:
The project scope includes the design and building of a pipeline to perform document clustering based on a variety of methods, summarizations based on a similarity function, and topic classification prediction. The motivation behind this project is that often, widely accessible documents on the internet where search and categorization are usually easy, the challenges related to this approach including the quality of useful hits and logical summaries are hard to generate. This project entails the clustering, classification, and summarization of these documents into multi-topic domains. There are various methods applied to this field yielding great success; however, there are many challenges which include, documents being multi-topical, the inclusion of professional, domain-specific language across a broad and uneven spread of issues, and lack of gold standard, ground truth data on proper summaries. Document classification can be very beneficial to supplement the traditional, often manual analysis and interpretation of the legal text corpora. Many algorithms view a document as a single unit and is not segmented into further topics. This project outcome would be able to provide the user with extensive, topic-related results matching the scope of which the documents are of interest or relevance through the model further providing useful summaries.

## Significance and User Cases Driving Development:
How the documents are organized for review can make a big difference in the efficiency of systematic review and search, not only saving costs but also improving accuracy by assigning similar documents to the same reviewer. Clustering algorithms examine the text in the documents, determines which documents are related to each other, and groups them into similar categories. This can be further segmented into related sub-topics. Clustering makes it easy to explore and categorize “big data” sets of documents, bringing efficiency to the electronic discovery process. An efficient document browsing and navigation is a valuable complement to the deficiencies of traditional Information retrieval technologies.

## Dataset
The CNN and Daily Mail Dataset contains the documents and accompanying questions from the news articles. There are approximately 287k documents and 1260k questions collectively in this dataset.

https://github.com/abisee/cnn-dailymail

https://github.com/huggingface/datasets/tree/master/datasets/cnn_dailymail

## Objectives and Milestones

1. We will try to achieve maximum output by applying multiple techniques in our analysis as time permits.
> The proposal, research (reading through and implementing a base text clustering, classifying and text summarizing tutorial(s))
> EDA; naive document clustering and visualizations.
> Model training / additional model integration.
> Model evaluation and analysis, Retraining model, and improving results Building robust results visualizations.
> Final presentation built

2. Project-specific objectives
* Text Documents:
> Gathering text document datasets for training, testing, and validating purposes.
* Data preprocessing
> Data cleaning - remove these stop words to avoid getting these stop words as topic terms
* Perform data analysis
> Extract features from the data, identify bags of words, and the frequency of terms appearing in each category.
* Exploring and applying various similarity functions to cluster, classify data
> Cosine similarity
> k-means
* Evaluate model performance
* Data visualizations to represent clusters and groups

## Features and Design
1. Programming languages 
> Python 
2. Modules 
> Backend - model development using Tensorflow/Pytorch CNN model
> NLTK/SpaCy
> Stanza
> Matplotlib
> Jupyter notebook or Google Colab
3. Features
> This program will have a pipeline to take in documents and perform clustering and visualizations of the distribution, and generate a summarization.
> This program will have a topic prediction classification.
> This project will have a summary evaluation metric to determine the quality of the summary

## Resources and Related Projects
https://beckernick.github.io/law-clustering/
https://research.ijais.org/volume2/number6/ijais12-450384.pdf
https://cs.nyu.edu/~kcho/DMQA/

https://medium.com/better-programming/extractive-text-summarization-using-spacy-in-python-88ab96d1fd97
> This tutorial implements extractive text summarization using spaCy in Python. Our goal is to implement a similar text summarization algorithm using Stanza instead.
Mihalcea, R., & Ceylan, H. (2007). Explorations in Automatic Book Summarization. Proceedings of the 2007 Joint Conference on Empirical Methods in Natural Language Processing and Computational Natural Language Learning, 380–389.
> An article on summarization methods.
Qi, P., Zhang, Y., Zhang, Y., Bolton, J., & Manning, C. D. (2020). Stanza: A Python Natural Language Processing Toolkit for Many Human Languages. Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics: System Demonstrations, 101–108. https://doi.org/10.18653/v1/2020.acl-demos.14 
> The paper introducing Stanza
