# CS7641 Project Fake News Detection Algorithm


## 1. Introduction 

Fake news on social media has experienced a resurgence of interest due to the recent political climate and the growing concern around its negative effect. Not only does it provide a source of spam in our lives, but fake news also has the potential to manipulate public perception and awareness in a major way. The amount of disseminated information and the rapidity of its diffusion make it practically impossible to assess reliability in a timely manner, highlighting the need for automatic fake news detection systems. In that spirit, our project centers around building a fake news detect system for text content based on data collected from news articles.

 

We start with a brief description of the data set used in the development of this system and the metric we used to measure performance, followed by each of the various approaches and algorithms we implemented.

## 2.Data set and Basic idea

The data set used in training and testing the detection systems comes from Kaggle fake news. Kaggle is an online community of data scientists and machine learning practitioners and offering public datasets for algorithm testing. Kaggle fake news dataset is a set of 20799 news article with fake (or not) label. Each data has 5 attributes: 


1. id: unique id for a news article;
2. title: the title of a news article; 
3. author: author of the news article; 
4. text: the text of the article (could be incomplete); 
5. label: a label that marks the article as potentially unreliable, 1 for unreliable and 0 for reliable.

 In this project, our work mainly surrounding text analysis of fake news. We focused on mining particular linguistic cues, like, by finding anomalous patterns of pronouns, conjunctions, and words associated with negative emotional word usage. For example, that fake news often contains an inflated number of swear words and personal pronouns. The raw news be represented using the Bag-of-Words model, which then be modified to incorporate the relativity between the words. We used both supervised and unsupervised learning here.  For unsupervised learning, we used GMM and Kmeans; for supervised learning, we take a try at LSTM and a two layer neural network.

## 3.Unsupervised Method



## 4.Supervised Method



## 5.evaluation and results 

![](https://github.com/ksun86/ML-Project/blob/master/fig1.png)  

![](https://github.com/ksun86/ML-Project/blob/master/percent_capital.png)  

![](https://github.com/ksun86/ML-Project/blob/master/similar_words.png)  

![](https://github.com/ksun86/ML-Project/blob/master/title_length.png)   Example Readmes



## 6.conclusions



## References

1. Ward A, Ross L, Reed E, et al. Naive realism in everyday life: Implications for social conflict and misunderstanding[J]. Values and knowledge, 1997: 103-135.
2. Nickerson R S. Confirmation bias: A ubiquitous phenomenon in many guises[J]. Review of general psychology, 1998, 2(2): 175-220.
3. Shu K, Sliva A, Wang S, et al. Fake news detection on social media: A data mining perspective[J]. ACM SIGKDD Explorations Newsletter, 2017, 19(1): 22-36.
4. Thota, Aswini, et al. “Fake News Detection: A Deep Learning Approach.” SMU Data Science Review, vol. 


