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
* Our project was to create an app that would identify cyberbullying on a social media website.
* Implement the use of natural language processing to create an algorithm that would be able to recognize if a line of text was considered cyberbullying.
* In addition, we wanted to create an application that would be able to identify cyberbullying from newly created text.
* To build our model and our sample social media site, we used HTML, CSS, Bootstrap, JavaScript, JQuery, Python, Flask, Scikit-Learn, Beautiful Soup, Natural Language Toolkit, PySpark and various other libraries.


## Data
Our data was obtained from Kaggle (https://www.kaggle.com/dataturks/dataset-for-detection-of-cybertrolls)

![kaggle](https://raw.githubusercontent.com/ajkim19/Cyberbullying_Sentiment_Analysis/master/Resources/kaggle-logo-gray-300.png)

The json dataset was turned into a Pandas dataframe 

Two columns were removed so that only the columns of the text and the rating remained

Another dataset was imported and later merged with the previous dataset. This dataset contained tweets from anonymous president and an anonymous politician. The tweets were then manually classified as cyberbullying or not cyberbullying using ones and zeros.

Variations of machine learning models were tested, including word count, term frequency-inverse document frequency, and naive bayes. Eventually, we settled on the support vector machine using n-gram vectorization.

![jupyter_notebook](https://github.com/ajkim19/Cyberbullying_Sentiment_Analysis/blob/master/NLP%20Machine%20Learning%20Project%20(final).ipynb)


## The Cyberbullying Application

We pseudo social media site was created. At the bottom of the website, there is an input window where comments could be added.

![social_media_site](https://raw.githubusercontent.com/ajkim19/Cyberbullying_Sentiment_Analysis/master/Resources/social_media_site.PNG)

The key component of the website is the "Find Bullies" button. By clicking on the button, comments identified as cyberbullying would be marked/highlighted in red.

![social_media_site_postmarking](https://raw.githubusercontent.com/ajkim19/Cyberbullying_Sentiment_Analysis/master/Resources/social_media_site_postmarking.PNG)

The concept is to show that there is a possibility an application could analyze social media sites, such as twitter or facebook, to identify and potentially protect individuals from cyberbullying.
The application that we created is not perfect because of the complexities of the English language, which include the evolution of connotations and slang, but for it works well in identifying straightforward insults and vugarity.




### References
* https://www.stopbullying.gov/cyberbullying/what-is-it/index.html
* https://cyberbullying.org/summary-of-our-cyberbullying-research
