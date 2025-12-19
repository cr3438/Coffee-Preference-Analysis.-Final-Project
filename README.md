# Coffee-Preference-Analysis.-Final-Project
This project analyzes coffee preference data from the TidyTuesday Survey "The Great American Coffee Taste Test" the idea is to explore how people evaluate different coffees. 
Important for context: 
Coffees A, B, and C are made from the same Kenyan coffee beans, roasted at light, medium, and dark levels.
Coffee D is a Colombian coffee processed using an experimental method that produces more fruity and fermented flavor    
notes.
Using R the project aimed to answer the following questions: 
1. Which coffee sample (A, B, C, or D) is liked the most?
2. Does gender influence coffee taste perceptions?
3. Is there a great difference in preference between Coffee A and Coffee D? Since A and D were the most preferred in the entire sample
4. Do bitterness and acidity predict how much someone likes a coffee?

Instructions on How to Run the Code
1. Either use R and RStudio to open the code sheet. I used GoogleColab
2. Make sure all required R packages are installed (See below the requirements
3. Press "Run" in order to activates the code from top to bottom. To avoid errors.
4. The code will read the dataset "raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2024/2024-05-14/coffee_survey.csv"
5. The code will read all the information including statistical models and graphs

These are the R packages are needed:
1.readr
2.tidyr
3.dplyr
4.ggplot2
5.viridis
Some graphs ideas were inspired by examples from the R Graph Gallery (https://r-graph-gallery.com/)

Results
1. Coffee D was the favorite among participants with a mean of 3.37. Coffee A had a mean score of 3.31. Coffee B and Coffee C were rated lower, both around 3.06.
2. Results from the paired t-test were signficant t(3755) = -2.40, p = 0.0165 Coffee D is preffered by not by much. 
3. Preference on bitterness, and acidity ratings were similar across genders, but the sample included a bigger number of male responses, which may affect the overall distributions.
4. Participants tended to dislike coffees they perceived as more bitter. However, acidity had mixed relationships, increasing liking for some coffees while decreasing it for others. For instance, the higher the acidity there was lower preference for Coffees A and D, but there was a positive relationship with preference for Coffee C, and little to no effect on preference for Coffee B.
