# Hotel Review NLP 
The goal of this project is to build unsupervised Natural Language Processing (NLP) machine learning models that decide whether a text review
is positive review or negative review. Then, it will find the topics based on the most common words in each type.

To start with, the data has been cleaned by dropping duplicated and empty reviews. Also, the non-English reviews has be removed, as well as punctions, 
repeated characters  the data has been split into two types to analyze each type individually.

<img width="1242" alt="Screen Shot 1443-04-11 at 5 25 52 PM" src="https://user-images.githubusercontent.com/90555117/142011537-2d86e3dc-9792-4008-adee-df90bf824c91.png">
 
The figure above shows the most common review words. The dark blue dots in the figure represent the most frequent positive words and the red dots 
represent the most common words in the negative reviews. Also, the most common words in each type are shown in the right section of the figure.

The next steps, from the above figure, the data needs more cleaning, such as removing stop word and abbreviations. Then, clustering the hotels that are 
close to each other based on their latitude and longitude. Also, a recommendation system from the user nationalities and their review scores will be built in this the project.
