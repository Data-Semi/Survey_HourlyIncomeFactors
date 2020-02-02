# Important factors to get high income with good work-life balance as a developer - Based on Stack Overflow Developer Survey 2019

1. Project Motivation  
Software developers has the image that doing lots of overtime work.  
However, there is some of them are having good income and also keeping there work-life balance good. Naturally, I asked myself: Can I be one of them? Is it too late for me? What should I do for that? With these question, I did a brief research with the 2019 Stack Overflow's annual Developer Survey.The survey includes nearly 90,000 developers answer.   

2. Packages Used    
The following packages are required to execute the code in the jupyter notebook. They all come with the [Anaconda Python distribution](https://www.anaconda.com/distribution/)
+ numpy
+ pandas
+ matplotlib
+ seaborn  

In addition,I used a package for analysis as below.  
+ [FeatureSelector](https://github.com/WillKoehrsen/feature-selector)
    
3. Data Source  
The dataset for this analysis is from [Stack Overflow Annual Developer Survey 2019](https://insights.stackoverflow.com/survey/2019)  

4. Questions in Interest  
+ What programming language is popular in the "satisfied good earner" group?  
+ What kind of database is popular in the "satisfied good earner" group?  
+ How old and how many years coding as professional developer are they in the "satisfied good earner" group?  
+ What is the key factors in the "satisfied good earner" group?  

5.The files in the repository  
+ Data folder: Includes the survey files. 
+ Data/survey_results_public_proDev_10Countries.csv :It is abstracted "Professional Developers" in top 10 appearence of countries from the original survey file ["survey_results_public.csv"](https://drive.google.com/open?id=1QOmVDpd8hcVYqqUXDXf68UMDWQZP0wQV).  
+ feature_selector folder: A package I used for perform machine learning.
+ Images: Saved image files from the code.
+ TimePaidRanking.ipynb: Research notebook.

6. Results  
    If one person in around age 38–48 who taking lots of time to review code,and codde as profession many years, he/she has big chance to have good hourly income and work-life balance.  
    In the same age, people with longer code profession experience can earn better. Also, with the same years coded professionally, the youngest group and the oldest group earn better.  
    Good “hourly income” appears with developer types:“Academic researcher”, “Marketing or sales professional”, ”Scientist”, Languages: “Assembly”, ”Clojure”, ”VBA”.  
    Especially, “Marketing or sales professional” who use the language “Scala” have very good “hourly income”.  
    Good “hourly income” appears with Databases: “Cassandra”, ”Couchbase”, ”Redis”.  
    Especially, “Scientist” who use the database “Cassandra” have very good “hourly income”.  
    
For a bit more narrative, here's a link to my post and notebook:
+ [Blog Post](https://medium.com/@liangmhua/what-is-important-to-earn-money-with-good-work-life-balance-as-a-software-developer-eca04d9dd71e)
+ [Time paid Ranking.ipynb](https://github.com/Data-Semi/Data-Science/blob/master/TimePaidRanking.ipynb)
