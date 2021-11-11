# NLP Hotel Review Project Proposal
## Backstory & scope
For luxury hotels, it is very important to overlook the users feedback about their experience in the hotel and its services to improve and avoid negative 
things and keep the positives. Also, reviews can be analyzed to understand where a hotel failed to provide a good customer experience and where it succeed to do 
so. Therefore, booking.com has provided this great feature which allows customers to write text reviews about their experience in a hotel, to help the hotels and other costumers.

The goal of this project is to build unsupervised Natural Language Processing (NLP) machine learning models that decide whether a text review is positive review or 
negative review. This project, will help hotels to determine the category of text review and cluster them automaticity to improve their services.

## Data Description
The data for this project will be read into a CSV file (Find the dataset on the following [link](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe/discussion)). 
This dataset is a scraped data from booking.com contains 515,000 customer reviews (rows)  for 1493 luxury hotels across Europe and it has 17 columns as will. However, 
this data set has been manipulated to contain only two columns: review text , and its category (positive review 1 or negative review 0 ).

## Tools:
- SQLAlchemy to read the data and for easier data manipulation.
- Pandas library will be used to create data frames.
- NLTK toolkit to perform common NLP tasks.
- Sklearn library will be to implement the classification and clustering models.
- Matplotlib and Seaborn to visualize and discuss the results of the analysis.
