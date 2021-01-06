# Semantic-Analysis

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).

Number of reviews: 568,454<br>
Number of users: 256,059<br>
Number of products: 74,258<br>
Timespan: Oct 1999 - Oct 2012<br>
Number of Attributes/Columns in data: 10<br>

1.Id<br>
2.ProductId - unique identifier for the product<br>
3.UserId - unqiue identifier for the user<br>
4.ProfileName<br>
5.HelpfulnessNumerator - number of users who found the review helpful<br>
6.HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not<br>
7.Score - rating between 1 and 5<br>
8.Time - timestamp for the review<br>
9.Summary - brief summary of the review<br>
10.Text - text of the review<br>


* Remove Special characters <br>
* Remove stop words<br>
* Remove HTML Tags<br>
* Removing null coloumn<br>


AUC SCORE = 0.95 Using Pre-trained BERT Model
