# Amazon Vine Analysis

##Overview
We will use our tools(PySpark, SQL, and pgAdmin) to access, extract, filter, and transform Amazon vine data and databases to determine if there are any biases in the reviews.  With this information, we are able to help Jennifer with an extensive analysis to review with the Sellby stakeholders.

##Results
-How many Vine reviews and non-Vine reviews were there?

![This is an image](https://raw.githubusercontent.com/sadayas/Amazon_Vine_Analysis/main/Resources/total5r.png)

-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![This is an image](https://raw.githubusercontent.com/sadayas/Amazon_Vine_Analysis/main/Resources/5starnumbers.png)

-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviwes were 5 stars?

![This is an image](https://raw.githubusercontent.com/sadayas/Amazon_Vine_Analysis/main/Resources/5starperc.png)

##Summary
There can be a positive bias, as we can see there is over 50% of the 5-Star reviews to be paid.  While about 39% of 5-Star reviews are unpaid.  However with the total amounts in this study, the 5-Star paid reviews would not differ the bias to much from the total amount of reviews.
One extra analysis to be used is to help measure the predicted values and actual values with BinaryClassificationEvaluator and help determine the biases within the reviews.  We can also find out the entirety of all reviews and find the averages of total paid reviews and unpaid reviews.