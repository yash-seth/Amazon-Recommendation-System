# Abstract
Online E-commerce websites like Amazon, Flipkart use different recommendation
models to provide different suggestions to their users. Amazon currently uses
item-to-item collaborative filtering, which scales to massive data sets and produces
high-quality recommendations in real time. This type of filtering matches each of the
user's purchased and rated items to similar items, then combines those similar items
into a recommendation list for the user. In this project we are going to build a
recommendation model for the electronics products of Amazon. This recommendation
model adheres to the information network provided by the dataset and analyzes the
purchases and ratings made by other users to draw out trends and recommend ten
products the user may be interested in purchasing next.

# Dataset Description
Product reviews and metadata from Amazon, comprising 142.8 million reviews from May 1996
to July 2014, are included in this collection. This dataset consists of links (also viewed/also
bought graphs), product metadata (descriptions, category information, price, brand, and image
attributes), and reviews (ratings, text, helpfulness votes).
The dataset here is taken from the below website.
    
Source - Amazon Reviews data (http://jmcauley.ucsd.edu/data/amazon/).
    
The repository has several datasets. For this case study, we are using the Electronics dataset.
     
Attribute Information:
- userId : Every user identified with a unique id (First Column)
- productId : Every product identified with a unique id(Second Column)
- Rating : Rating of the corresponding product by the corresponding user(Third Column)
- timestamp : Time of the rating (Fourth Column)

# Module List
1. Importing the packages and Dataset
2. Initial Data analysis and Anomaly Detection
3. Preprocessing and Handling missing values
4. Popularity Based Recommendation System
5. Collaborative Filtering
6. Model Based Collaborative Filtering System

# Conclusion & Future Work
The above report highlights the approaches adopted to work on the product recommendation
system using machine learning techniques by taking the example of amazon product reviews
dataset. After the initial data cleaning the pre-processing adopted from the first three modules,
using the data visualization and data imputation process before working on the data, we were
able to comprehend and understand the nature of the data. This process helped us to outline the
extraction of the required knowledgeable data from the information network by favoring only
desirable categories for further processing.
    
To build a successful recommendation system for data extraction, we applied 3 commonly used
approaches and eliminating the drawbacks we were able to satisfy the accuracy results and
performance of the system.
    
Going with the trend, the popularity-based recommendation technique focuses on the new
arrivals and exploring the trends patterned by the consumers. The collaborative filtering based on
traditional statistical approaches works on the key features irrespective of the nature of the
dataset to highlight the similar taste of the consumers based on information network. Model
based collaborative filtering systems take the approach ahead by using different machine
learning algorithms to find similarities between users or between items based on recorded
user-item preferences.
    
Hence, by applying multiple approaches the results were found in sync with a good percentage of
accuracy. The three modules successfully nullified each other’s drawback of cold-start problem,
accommodating new entries to improve prediction analysis.
    
Today, we have a plethora of choices on product and services offered by different service
providers but such recommendation systems are on rise as the companies need some way of
curating content for customers as browsing millions of options doesn’t stand feasible. More of
the recommendations and item to item similarity, the systems today are seen more as an effective
way to understand similarity of latent attributes using matrix factorization. Such information
networks are simplified to reveal relations yet not realized.
    
Future of recommendation eyes on concepts of Deep Learning and Neural networks and work
credits to development of multiple such systems. The product recommendation could be taken to
next level apart from accuracy and precision, to exploit the benefits of Deep Learning to the
matrix factorization analyzing the ability to derive latent attributes by making up for the
weaknesses to include time attribute in the model which isn’t implemented as of now.
Another attempt could be made to utilize Recurrent Neural Networks which are specifically
designed for time and sequence data. Thus, big data like Amazon has time, month, week and an
important factor in understanding consumer preferences and impacting shelf life of its products.
Attempts have been made to highlight the sub-optimal recommendation from the user as its
function would be to show customers a recommendation and record consumer habits to improve
learning in the long term.
    
Hence, such recommendations prove to be favorable for any sales or business models to generate
multiple folds as some of the applications include being able to anticipate seasonal purchases
based on recommendations, determine important purchases and give better recommendations to
customers to increase retention and brand loyalty.
