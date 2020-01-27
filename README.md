# SMS Spam Detection
This [Github](https://github.com/prince381/spam_detection) repository contains the files and other resources for my machine learning project which entails training a text classification model to detect spam messages. The code associated with this project is written in python programming language in a jupyter notebook with the file extension '.ipynb' .

## Text Classification
Text classification is one of the most important task in Natural Language Processing. It is the process of classifying text strings or
documents into different categories, depending upon the contents of the strings. Text classification has a variety of applications, such
as detecting user sentiment from tweets, classifying an email as spam or ham, classifying blog posts into different categories, automatic
tagging of customer queries, and so on. This process can be done manually (carried out by a human agent who reads texts and categorizes
them) or automatically (which involves machine learning algorithms that will classify your texts in a faster and more cost-effective way).

## Project description and workflow
In this project, I will demonstrate a real world example of text classification using machine learning. The goal of this project is to
train a text classification machine learning model in python capable of predicting whether a text message is spam or not. I will use
python’s Scikit-learn library for machine learning to train the text classification model and below are the following steps I will go
through in the jupyter notebook to train the text classification model:
* Importing the libraries needed
* Importing the data set
* Text preprocessing
* Converting text to numbers
* Splitting the data into train and test sets
* Training the text classification model and predicting SMS messages as spam or ham
* Evaluating the  model
* Saving and loading the model

## About the data
The data that will be used in this project is the SMS Spam Collection v. 1 created by Tiago A. Almeida and José María Gómez Hidalgo  and
can be downloaded from [www.dt.fee.unicamp.br/~tiago/smsspamcollection/smsspamcollection.zip](www.dt.fee.unicamp.br/~tiago/smsspamcollection/smsspamcollection.zip). The SMS Spam Collection v.1 is a public set of SMS labeled messages that have been collected for mobile phone
spam research. It has one collection composed by 5,574 English, real and non-encoded messages, tagged according being legitimate (ham)
or spam. This corpus has been collected from free or free for research sources at the Internet and the composition of the data set are
listed below:
* A collection of 425 SMS spam messages was manually extracted from the Grumbletext Web site. This is a UK forum in which cell phone users make public claims about SMS spam messages, most of them without reporting the very spam message received. The identification of the text of spam messages in the claims is a very hard and time-consuming task, and it involved carefully scanning hundreds of web pages. The Grumbletext Web site is: [http://www.grumbletext.co.uk/](http://www.grumbletext.co.uk/).
* A subset of 3,375 SMS randomly chosen ham messages of the NUS SMS Corpus (NSC), which is a data set of about 10,000 legitimate messages collected for research at the Department of Computer Science at the National University of Singapore. The messages largely originate from Singaporeans and mostly from students attending the University. These messages were collected from volunteers who were made aware that their contributions were going to be made publicly available. The NUS SMS Corpus is available at: [http://www.comp.nus.edu.sg/~rpnlpir/downloads/corpora/smsCorpus/](http://www.comp.nus.edu.sg/~rpnlpir/downloads/corpora/smsCorpus/).
* A list of 450 SMS ham messages collected from Caroline Tag's PhD Thesis available at [http://etheses.bham.ac.uk/253/1/Tagg09PhD.pdf](http://etheses.bham.ac.uk/253/1/Tagg09PhD.pdf). 
* Finally, we have incorporated the SMS Spam Corpus v.0.1 Big. It has 1,002 SMS ham messages and 322 spam messages and it is public available at: [http://www.esp.uem.es/jmgomez/smsspamcorpus/](http://www.esp.uem.es/jmgomez/smsspamcorpus/).

#### Reference:

Almeida, T.A., Gómez Hidalgo, J.M., Yamakami, A. Contributions to the Study of SMS Spam Filtering: New Collection and Results.
Proceedings of the 2011 ACM Symposium on Document Engineering (DOCENG'11), Mountain View, CA, USA, 2011

Gómez Hidalgo, J.M., Almeida, T.A., Yamakami, A. On the Validity of a New SMS Spam Collection. Proceedings of the 11th IEEE
International Conference on Machine Learning and Applications (ICMLA'12), Boca Raton, FL, USA, 2012. 

Almeida, T.A., Gómez Hidalgo, J.M., Silva, T.P. Towards SMS Spam Filtering: Results under a New Dataset. International Journal of Information Security Science (IJISS), 2(1), 1-18, 2013.

