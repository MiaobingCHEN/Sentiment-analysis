# Sentiment-analysis
This projet aim at develop a system of sentiment analysis for a product or a service. In analysing the sufficient reviews of the products of a domain, we define some propre fecteurs of the review, which will help distinguish its sentiment. The sentiments can be multiple. One typical example is the positive or negative sentiment.   
In this projet, we have applied two methods to create sentiment analyzer. One is based on the dictionary of positive and negative words, with the semantic analyse: negative sentences, adverbs of degree, punctuation, conjunction "but", etc. The other one is based on the classification algo Bayes, well known in the machine learning domain. 

## Description
>**Sentiment analysis** (sometimes known as opinion mining or emotion AI) refers to the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information. Sentiment analysis is widely applied to voice of the customer materials such as reviews and survey responses, online and social media, and healthcare materials for applications that range from marketing to customer service to clinical medicine.  
  
>Generally speaking, sentiment analysis aims to determine the attitude of a speaker, writer, or other subject with respect to some topic or the overall contextual polarity or emotional reaction to a document, interaction, or event. The attitude may be a judgment or evaluation (see appraisal theory), affective state (that is to say, the emotional state of the author or speaker), or the intended emotional communication (that is to say, the emotional effect intended by the author or interlocutor).

## Contributor
* Miaobing CHEN
* Rui SUN

## Stuff of developpement
* Python 3.x
* NLTK
* panda

## Usage
Use analyzer based on the classification algo Bayes
```
>python sentiment_analyzer_dict_complete.py "Sentence for analyze"
```
Use analyzer based on the dictionary of emotional words with semantic analyse
```
>python sentiment_analyzer_classification.py "Sentence for analyze"
```
We can analyze several sentences seperated by space at the same time.

## Resources Descriptions
* **Test.py**  
  Test for two analyzer 
  
* **sentiment_analyzer_classification.py**   
  Analyzer based on the classification algo Bayes
  
* **sentiment_analyzer_dict_complete.py**  
  Analyzer based on the dictionary of emotional words with semantic analyse
  
* **SentiWordNetReader.py**  
  Source code for reading SentiWordNet and write the file **SentiWordNet_simple_format.txt**
  
* **SentiWordNet_simple_format.txt**  
  Lexicon in a simple format generated by SentiWordNet
  
* **degree.txt**  
  A list of adverb of degree, collected from http://en.wiktionary.org/wiki/Category:English_degree_adverbs
  
* **negation.txt**  
  A lsit of words or expression that means negation of sentence

## Reference
* https://en.wikipedia.org/wiki/Sentiment_analysis
* https://en.wikipedia.org/wiki/Natural_language_processing
* Dataset: http://times.cs.uiuc.edu/~wang296/Data/
* SentiWordNet: http://sentiwordnet.isti.cnr.it/
