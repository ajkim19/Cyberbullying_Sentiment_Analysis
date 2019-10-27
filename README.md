# Cyberbullying Sentiment Analysis

## Background

### What is cyberbullying?
* Cyberbullying is bullying that takes place over digital devices like cell phones, computers, and tablets. Cyberbullying can occur through SMS, Text, and apps, or online in social media, forums, or gaming where people can view, participate in, or share content.
* Cyberbullying includes sending, posting, or sharing negative, harmful, false, or mean content about someone else.

### What are its effects?
* Kids who are bullied can experience negative physical, school, and mental health issues. Kids who are bullied are more likely to experience:
	* Depression and anxiety, increased feelings of sadness and loneliness, changes in sleep and eating patterns, and loss of interest in activities they used to enjoy. These issues may persist into adulthood.
	* Health complaints
	* Decreased academic achievement—GPA and standardized test scores—and school participation. They are more likely to miss, skip, or drop out of school.

* Research also shows that the rates of cybullying are increasing. 
![Cyberbullying Reasearch Graph](https://raw.githubusercontent.com/ajkim19/Cyberbullying_Sentiment_Analysis/master/misc/Cyberbullying_Victimization_all_studies_2019.jpg)
* This is possibly due to the greater accessibility of mobile devices and social media to children.


## Objective
* Our project was to use natural language processing to create an algorithm that would be able to recognize if a line of text was considered cyberbullying.
* In addition, we wanted to create an application that would be able to identify cyberbullying from newly created text.
* To build our model and our sample social media site, we used HTML, CSS, Bootstrap, JavaScript, JQuery, Python, Flask, Scikit-Learn, Beautiful Soup, Natural Language Toolkit, PySpark and various other libraries.


## Data
Our data was obtained from Kaggle (https://www.kaggle.com/dataturks/dataset-for-detection-of-cybertrolls)

![kaggle](insert_image)

The json dataset was turned into a Pandas dataframe 

![original_df](insert_image)

Two columns were removed so that only the columns of the text and the rating remained

![cleaned_df](insert_image)

Another dataset imported. This dataset contained tweets from and 



### References
* https://www.stopbullying.gov/cyberbullying/what-is-it/index.html
* https://cyberbullying.org/summary-of-our-cyberbullying-research
