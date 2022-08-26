# Project Title

![microsoft logo](https://user-images.githubusercontent.com/103558721/186992195-44c91ac0-ed90-4804-a6e0-9eabd3b639f5.PNG)


## Overview
Microsoft Corporation is a multinational technology corporation known for their manufacturing of consumer electronics as well as software and other IoT related services.  In comparison to other tech giants like Amazon or Apple, Microsoft does not currently have its own operations for creating original video content. Should Microsoft choose to diversify and “throw it’s hat” into movie making, what would they need to do to ensure success?


## Business Understanding
If Microsoft or any organization were to consider breaking through to the film and movie making industry, how can we leverage and utilize data from various online sources (including databases) to develop a strategy worth investing in as it both generates ideal return or profit whilst minimizing risk. The questions we aim to answer are: 
-	Who are the top production studios in the industry and what genres are they capitalizing on?
-	As a new studio, should we choose to compete in those genres or are there profitable alternatives?
-	How much of an investment is needed to reach sustainable profit (long term)?
-	Are there additional trends successful franchises share that we can capitalize on?  
-	After understanding the type of film to be profitable and the level of investment needed, how do we determine the talent that will ensure success of this project?



## Data Understanding and Analysis


Through a combination of web-scraped data (The Numbers, Rotten Tomatoes, Box Office Mojo, The Movie database)  and querying the Internet Movie Database (IMDB), we cleaned/scrubbed/merged data from various tables to create data frames we could use to:

-	Calculate ROI and Profit margin for all films using Production Budgets (cost) and Box Office Gross (revenue)  

-	Identify the median for profit margins to determine most profitable genre

![profit margin by genre](https://user-images.githubusercontent.com/103558721/186993232-faee72ff-663f-4f37-b055-27233e9fafbf.PNG)




-	Calculate the total box office gross for each studio to identify market share of competitors 

![market share by studio](https://user-images.githubusercontent.com/103558721/186993179-cee3a340-7ead-4768-9723-b853df4b6edc.PNG)


-	Find the breakdown of movies for each genre produced by studios with largest market share 

![moviecount by genre](https://user-images.githubusercontent.com/103558721/186998803-b5b32e82-0546-4f9c-b723-5e5068919f5b.PNG)




-	Calculate the total number of movies in each genre (from every studio) to find market saturation

![market saturation profit margin](https://user-images.githubusercontent.com/103558721/186993476-399af069-7ed1-4273-b24f-a0ccd3786b81.PNG)


- Found median profit margin of top grossing films in each of the top studios to calculate average 
![median profit margin](https://user-images.githubusercontent.com/103558721/186992936-b208bd3e-931e-41b1-8ae9-2ae2f1abf1d7.PNG)

- Compare relationship between Production Budget and Profit Margin 
![budget v profit margin](https://user-images.githubusercontent.com/103558721/186993527-9352f12e-8e2b-4e03-af44-717c7677798e.PNG)

-	Use average of median profit margins to determine ideal investment threshold 

![ideal movie budget](https://user-images.githubusercontent.com/103558721/186993648-1f5a2a95-c149-4704-a96b-f8dd37febb36.PNG)



-	Find 'buzzwords' commonly used in titles of successful movie 

![buzzwords](https://user-images.githubusercontent.com/103558721/186993680-362d5e21-bef8-49c7-8b60-6e6ca95b7221.PNG)


- For Sci-Fi, the word "Alien" was found in movies with high ROI's vs. the word "Mars" which fared poorly in terms of ROI

![scifi movie title boxwhisker](https://user-images.githubusercontent.com/103558721/186994607-d0f66f1d-9a7c-4b7e-ab2c-287a8bb2ee04.PNG)


- For Thrillers, the words "night" and "evil" were found in movies with high ROI's, conversely the words "blood" and "dead" were found in movies with lower ROI's

![thriller movie title boxplot](https://user-images.githubusercontent.com/103558721/186995380-08da715d-fc06-4ef5-9cbe-eb2611c02acf.PNG)



-	Identify Directors who have directed a minimum of 3 movies (in each respective genre) with the highest ROI's
For Sci-Fi, we have Francis Lawrence (known for the Hunger Games) - with a median ROI above 10 (100%)

![scifi director](https://user-images.githubusercontent.com/103558721/186995007-4179ffe8-68f8-4faa-8096-e3c8a1a5f7d4.PNG)

![hungergames](https://user-images.githubusercontent.com/103558721/186995141-975fd744-3802-40f4-b413-bda0452416fe.PNG)

For Thrillers, we found Henry Joost (known for Paranormal Activity) to have ROI above 30 (300%)

![thriller director](https://user-images.githubusercontent.com/103558721/186995252-f8ca3524-60a2-4959-875c-ba5bdf0f759c.PNG)

![paranormal activity](https://user-images.githubusercontent.com/103558721/186995257-337eed0a-651e-452d-b943-74383fc015ed.PNG)


## Conclusion

After simulating various calculations and plots to find insights in the data that provided relevant and implementable towards our objective, we came to these conclusions.


### Of the most profitable genres with the least amount of saturation (movies) and little to no presence (competition) from the other big studios, Sci-fi and Thrillers proved to have the most opportunity for breakthrough 

### The ideal budget threshold is about $90 million 

### The talent we recommend are directors in each genre; Francis Lawrence for Sci-Fi and Henry Joost for Thriller



View presentation here: [Consulting Proposal Presentation.pdf](https://github.com/LindstromKyle/DSC-Flatiron-Project-1/files/9436509/Consulting.Proposal.Presentation.pdf)
