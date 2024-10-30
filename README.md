**Project Overview**

**• Objective:** Perform sentiment analysis on Amazon Alexa reviews to classify feedback as
positive or negative.

**• Dataset:** Amazon Alexa user reviews dataset with features such as rating, variation,
verified reviews, and feedback.

**Algorithms used in this project**:

1. Random Forest:
   
Random Forest helped classify the product reviews by learning from multiple decision trees,
capturing various patterns in the data. It’s effective at handling large datasets and is
resistant to noise.

Training Accuracy: 0.9945553539019963

Testing Accuracy: 0.9396825396825397

2. XGBoost:

XGBoost is utilized to boost the classification performance further, refining
the model by learning from errors made in previous iterations. It’s highly effective for text
classification problems due to its focus on reducing bias and variance.

Training Accuracy: 0.971415607985481

Testing Accuracy: 0.9417989417989417

**Dataset Details:**

Name: Amazon Alexa Reviews Dataset

Source: The dataset was sourced online, containing product reviews for Alexa
devices.

Attributes:

o Rating: The review rating on a scale from 1 to 5.

o Reviews: The actual text reviews given by the customers.

o Date: When the review was posted.

o Variation: Different variations of the product reviewed.

 Target: Sentiment label (positive or negative), created from the Rating column.

Reviews with ratings 4 and 5 were labelled positive, while 1 to 3 were labelled
negative.
