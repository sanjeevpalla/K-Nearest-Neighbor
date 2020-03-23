<h1>Amazon Fine Food Reviews Analysis</h1>

<h2>Data Source:</h2>  https://www.kaggle.com/snap/amazon-fine-food-reviews

<h2>EDA:</h2> https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/

<h2>About Dataset:</h2>
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454<br>
Number of users: 256,059<br>
Number of products: 74,258<br>
Timespan: Oct 1999 - Oct 2012<br>
Number of Attributes/Columns in data: 10<br>

<h3>Attribute Information:</h3>

1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review

<h2>Objective:</h2>
Given a review, determine whether the review is positive (rating of 4 or 5) or negative (rating of 1 or 2).<br>

<h5>[Q]</h5> How to determine if a review is positive or negative?
<h5>[Ans]</h5> We could use Score/Rating. A rating of 4 or 5 can be cosnidered as a positive review. A rating of 1 or 2 can be considered as
negative one. A review of rating 3 is considered nuetral and such reviews are ignored from our analysis. This is an approximate and
proxy way of determining the polarity (positivity/negativity) of a review.
