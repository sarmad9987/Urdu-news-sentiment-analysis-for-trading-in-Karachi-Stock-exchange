
# Urdu news sentiment analysis for trading in Karachi stock exchange

## Introduction:
We have compared state-of-the-art transformer language models such as BERT-multilingual and Roberta-Urdu-small in this project to see if large multilingual language models have an advantage over the monolingual language models in text classification/sentiment analysis. We have proposed our own classifier model in which we have combined transformer language models with Convolution neural networks (CNN). The last hidden state of the transformer was fed to Conv-1D layer and then softmax activation function was applied for multiclass-classification. The predicted sentiments were then used as trading signals to trade in karachi stocks and observe the returns. 



## Workflow

Complete workflow of the project is given below:

**1.** **Pre-processing to models training:** [click here for code](https://github.com/sarmad9987/Urdu-news-sentiment-analysis-for-trading-in-Karachi-Stock-exchange/blob/main/Model%20training/Model%20training%20.ipynb)

**2.** **Train models with random oversampling technique of imbalanced dataset:** [click here for code](https://github.com/sarmad9987/Urdu-news-sentiment-analysis-for-trading-in-Karachi-Stock-exchange/blob/main/Model%20training/Models%20training%20oversampled%20dataset.ipynb)

**3.** **Keyword extraction and visualization:** [click here for code](https://github.com/sarmad9987/Urdu-news-sentiment-analysis-for-trading-in-Karachi-Stock-exchange/blob/main/Keyword%20Extraction/Keywords_extraction.ipynb)
  
**4.** **Load Trained models for classification:** [click here for code](https://github.com/sarmad9987/Urdu-news-sentiment-analysis-for-trading-in-Karachi-Stock-exchange/blob/main/Load%20trained%20models%20for%20classification/Models_labels%20.ipynb)

**5.** **Trading Returns with different strategies:** 
  
  * mBert+CNN: [click here for code](https://github.com/sarmad9987/Urdu-news-sentiment-analysis-for-trading-in-Karachi-Stock-exchange/blob/main/Trading%20Returns/mBert%2BCNN%20Returns.ipynb)  
  * Roberta-Urdu+CNN: [click here for code](https://github.com/sarmad9987/Urdu-news-sentiment-analysis-for-trading-in-Karachi-Stock-exchange/blob/main/Trading%20Returns/Roberta%2BCNN%20Returns.ipynb)  


## Libraries and frameworks

This is just to mention what libraries and frameworks were used to complete this project.

* Pandas for analysis

* Urduhack for text pre-processing

* Tensorflow for deep learning models training 

* Keras (Python deep learnign API)

* Hugging face transformers

* Yake (yet another keyword extractor) for keyword extraction

* Wordcloud for Python for data visualization


## keywords visualization

Visualization of Urdu keywords in our dataset and also their English translation for non-Urdu speakers.

*                                                    **Urdu keywords**




![use this](https://user-images.githubusercontent.com/90148389/196811220-a724290f-8c35-4449-9a34-3887436803ac.jpg)



*                                              English translated keywords
 



* ![Screenshot 2022-10-16 195439](https://user-images.githubusercontent.com/90148389/196811326-8c0f68f9-796f-44ee-b3a3-31b78c4a2187.jpg)
