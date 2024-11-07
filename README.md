# Amazon Coupon Acceptance

In this project we explored a data set that included information such as: 
1. User attributes
    -  Gender: male, female
    -  Age: below 21, 21 to 25, 26 to 30, etc.
    -  Marital Status: single, married partner, unmarried partner, or widowed
    -  Number of children: 0, 1, or more than 1
    -  Education: high school, bachelors degree, associates degree, or graduate degree
    -  Occupation: architecture & engineering, business & financial, etc.
    -  Annual income: less than \\$12500, \\$12500 - \\$24999, \\$25000 - \\$37499, etc.
    -  Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
    -  Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater
    than 8
    -  Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or
    greater than 8
    -  Number of times that he/she eats at a restaurant with average expense less than \\$20 per
    person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
    -  Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
    

2. Contextual attributes
    - Driving destination: home, work, or no urgent destination
    - Location of user, coupon and destination: we provide a map to show the geographical
    location of the user, destination, and the venue, and we mark the distance between each
    two places with time of driving. The user can see whether the venue is in the same
    direction as the destination.
    - Weather: sunny, rainy, or snowy
    - Temperature: 30F, 55F, or 80F
    - Time: 10AM, 2PM, or 6PM
    - Passenger: alone, partner, kid(s), or friend(s)


3. Coupon attributes
    - time before it expires: 2 hours or one day

Throughout this project I used different python data anaylsis techniques to understand and identify certain trends within the data. Based on the acceptance rates, I noticed that people below 25 and those who do not have kids are more likely to accept coupons as oppose to people who are from the lower income category. This is a little bit surprising as I would expect drivers who are frequenting the restraunts more than 4 times and earn less than 50k would be using more coupons. However, the data for below 30 and no kids takes into account all types of restruants where as low income only takes into account the cheap restaurants and this may have an affect on the number of coupons accepted by each group. 

Looking at all the data that we observed above, I can also see that there was not much of a difference between the acceptance rates of people below 25 and frequented the the bars more than 1 time vs the those folks who were above the age of 25. However, when we look at Carry out & Take away coupons it is a different story. As we can see from the above chart, drivers below 25 were more likely to accept carry out & take away coupons as compared to their above 25 counter parts. This is most likely because these the below 25 demographic tends to perfer take out more than those in the above 25 population. This is interesting as well because the above 25 group was also more likely to accept the bar coupon as compared to the below 25 year old group. 
