# Amazon_Vine_Analysis

# Overview

The analysis uses data from reviews of a different category of products on Amazon and in this case pet products. Each review is are either vine-sponsored or non-vine-sponsored. The goal of this analysis is to see if there is any bias towards how the paid members rate vs the un-paid members.

Tools Used:
- PySpark
- Postgres SQL
- Amazon RDS

# Results 

1. How many Vine review and non-Vine reviews are there?
- There are 170 vine reviews vs 37840 unpaid reviews

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Out of the 20677 5-star reviews, only 65 were paid

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 38.2% of the Vine reviews were 5-stars, which leaves 54.5% of the reviews to people that were un-paid.


# Summary 

As the sample size in this data set is rather small with just 170 paid reviews, it is hard to conclude that there is much bias in the Vine program. Since there are significantly more non-vine reviews than vine reviews it makes it more complicated to get a reliable comparison. However judging off of only the data available it would appear that participation in the program does not mean better reviews as the paid reviews had a lower percentage of 5 star reviews (38.2%) than that of the non paid reviews (54.5%). 

