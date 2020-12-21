# Classifcation-tunisian-dialects

Tunisian text dialects presents a very complex language to understand by forgein citezness outside Tunisia. Therefore i aimed in this project to implement a deep learning model to automatically predict classify the postive from the toxic texts.
To do so, I made the following steps:

- I used #Silinuim to scrap the texts data from twitter to obtain a total of 32k rows.
- Second steps consists of labeling in binary way the scrapped data.
- I processed the data to make it ready for modelling.
- I used the recent introduced pretrained model ELECTRA to do the classfication task

## Articles

- ["ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators"](https://arxiv.org/abs/2003.10555) - *Kevin Clark et al.*
- ["A Hands-On Guide To Text Classification With Transformer Models"](https://towardsdatascience.com/what-you-should-have-on-your-data-scientist-resume-especially-in-the-pandemic-time-2bf15fbf8051) - *Thilina Rajapakse*

## Tools
-Jupyter Notebook
-Silinuim and BeautifulSoup
-Sikit learn & pandas
-Transformers library
