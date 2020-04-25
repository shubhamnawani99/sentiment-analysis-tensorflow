# Feedback Management System (Sentiment Analysis)
Natural Language Processing was used to automate the pre-existing feedback management system, easing the process of classification of individual reviews of customers and enabling to determine the overall rating of the product/service based on the individual reviews.

Using the above obtained analysis of the sentiment in review text, we can decide whether the review is a:  
5-star review: Excellent product; being extremely helpful to the user.  
4-star review: Good product; being useful to the user.  
3-star review: Average product; working well but minor improvement needed.  
2-star review: Fair product; working but major improvement needed.  
1-star review: Poor product; defective, not working at all.  
  
And after determining the type of review, it can be prioritized to be looked upon by the admin, with more critical or poorly rated reviews coming first on the list, which can be then read and worked upon.

# Technology Stack
Python Language  
Tensorflow deep learning framework  
Bi-directional Long-short term memory (BLSTM)  
Embedding Projector  
HTML/CSS/JavaScript  
Flask

# Dataset used
Amazon Review Data - http://jmcauley.ucsd.edu/data/amazon/

# Embedding Projector
To view how well the model has been trained, this projector helps to tell the relationship between the different words the model has learnt. Load the vecs.tsv and meta.tsv and then Sphereize data the see the relationship between different words and how they correspond to a rating.  
Link - http://projector.tensorflow.org/

# Show-stoppers  
Word ambiguity  
Too much noise in the dataset  
The training dataset can have false positives  
Dishonest feedback given by the user
