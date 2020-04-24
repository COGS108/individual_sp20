# COGS 108 - Project Proposal

# Names & PID

- Name: Alexis Doan
- PID: A14610025

# Research Question

Is there a relationship between the health inspection grading of restaurants in San Diego relative to Yelp consumer ratings?

## Background and Prior Work

Background and Prior Work:

San Diego county is the 8th most populated city in the United States, home to around 3.34 million people. It's approximately 14,000 retail food establishments are among the prime hot spot eateries you can find on Yelp, a popular website and app containing crowd-sourced user reviews/recommendations about restaurants and other businesses. User reviews can contain anything from how they rated the the friendliness of the staff to the wait time, menu variety, and most importantly the cleanilness of the restaurant and food preparation. Restaurants and food vendors must do their due diligence in making sure that they follow "food safety", the means of handling, preparing, and storing food in ways that prevent food-borne illness. Since the San Diego County Department of Environmental Health's food inspection program is in charge of keeping a close eye on the food safety of restaurants, I wanted to extend this information into observing whether or not there is a correlation between Yelp consumer ratings of restaurants in San Diego and the health inspection grading provided by the San Diego county system. Yelp's data will provide insight into restaurants that need more continual inspection or warning that the inspection scores may have missed.

From the San Diego County government agency it was found that counties throughout California inform the public of restaurant inspection results through different methods. San Diego specifically uses the grading system, where each violation on the Food Inspection Report is assigned a point value depending on its importance. For example, a Major Risk Factor is worth four points, a Minor Risk Factor is worth two, and a Good Retail Practice is worth one. Once the Specialist completes an inspection, the points are added up and subtracted from 100. The resulting number is the inspection "score". This "score" is a crucial part of the data I will use to map out the relationship between the condition of these restaurants (such as conditions that require closure of a food facility including, but not limited to: Sewage back-up, Lack of potable hot/cold water under pressure, Power outage for an extended period of time preventing proper holding temperatures of potentially hazardous foods, Active vermin infestation, and Disease transmission) in relation to Yelp's consumer reviews and overall ratings. I was able to find a previous group's final project on Github, which utilized Yelp reviews from Chicago to track which areas of crime are higher than others. Their research consisted of using Yelp's data, more specifically Yelp's API to understand how real consumers perceive the qualtiy of a restaurant. This is a valuable source of data as it provides me with information to compare and contrast the inspection results from the San Diego County government agency. Their research also made me aware that although Yelp has hundreds of various attributes when it comes to user reviews, I need to pick the specific attributes that apply to my research question and do a deep analysis of it. 

References (include links):
- 1) https://github.com/COGS108/FinalProjects-Sp17/blob/master/006-FinalProject.ipynb
- 2) https://www.sandiegocounty.gov/content/sdc/deh/fhd/ffis/intro.html.html

# Hypothesis


I predict that San Diego restaurants found on Yelp with high star ratings of 4 to 5 and large amounts of user reviews/bookmarks will correlate with official inspection scores of at least a B or higher. Restaurants rated by yelp users with 3 or lower stars and large amounts of user reviews will correlate with inspection scores of a C or lower.

Secondly, I predict that San Diego restaurants in wealthier communites of the county will receive both higher yelp and higher San Diego offical inspection scores leading to typically a B or higher grading while poorer/rural communities will receive lower ratings on yelp and an overall lower inspection grade. 

# Data

The ideal dataset for my proposed research question would consist of crowdsourcing data from Yelp’s user reviews/ Yelp's API as well as health scores related to all the restaurants in San Diego. I would specifically look at categories concerning commonalities between Yelp's own provided health score of the restaurant as well as how the consumers rated the overall restaurant based on a 4 or 5 attributes such as it's location in San Diego, the amount of times cleanliness/food prepartion is discussed in user reviews, the amount of stars given by users, and Yelp's own health inspection rating. Looking at San Diego County's offical inspection score I would look at the the grade recieved, notes of improvement, and how long the restaurant has been up and running. For observations, my data would consist of all the restaurants in San Diego (possibly using a sequence number instead of the restaurants name) that can be found on Yelp's website, and I will collect the overall ratings of each restaurant as well as the most popular/top reviews and comments, and the restaurants location. I will then collect the data from San Diego County's inspection scores of each of those restaurants. Additional data will be collected based on income level of communities in San Diego in regard to restaurant location. 

# Ethics & Privacy

For the purpose of this project, I will ensure that all datasets I use are released to the public by both Yelp and the San Diego county government in order to have reliable and comprehensive documentation of all data and sources I use. Given that the information provided by Yelp's API as well as the San Diego county government agency's inspection results is public, I believe I have permission to use this data in order to find correlations as long as there is no breach in privacy.

Considering my research question explores data provided by real users of Yelp who share personal information, I will remove all personal identification from the consumer reviews I use from yelp including name, location, age, etc. It is important that I maintain anonymity for all people involved from the consumers to the restaurant owners as I will omit any critical demographic information in my data and analysis.
