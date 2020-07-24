# Drug-Review-Sentiment-Analysis

With the advent of the internet, an increasing number of people are voicing their opinions online. Organizations are using these opinions to gain insight into how products and ideas are viewed. Healthcare organizations are looking at text data for tasks such as patient risk prediction, cohort selection and clinical decision support. Natural Language Processing (NLP) tools aid in extracting and analyzing structured as well as unstructured data from virtually any source.

Here, a sentiment analysis is performed on drug review data to determine if a review is positive, negative, or neutral. A variety of models were fit to the data, then hyper-parameter tuning was done on the top performing models. The data was web-scraped by crawling pharmaceutical review sites, specifically this dataset contains reviews from Drugs.com.

The data contains the following features:

1. drugName (categorical): name of drug
2. condition (categorical): name of condition
3. review (text): patient review
4. rating (numerical): 10 star patient rating
5. date (date): date of review entry
6. usefulCount (numerical): number of users who found review useful

https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29
