# Reading: 

**1,500 scientists lift the lid on reproducibility**
https://www.nature.com/news/1-500-scientists-lift-the-lid-on-reproducibility-1.19970

This is an article about the "crises of reproducibility". Read the article and inspect the figures carefully. You will be asked to describe one of the figure in the quizzes, its content, how to read it, and what it demonstrates (the take home point)



# Assignment 4

First: get a census API key - you have to request it by email

https://api.census.gov/data/key_signup.html

An API key comes with responsibilities (including legal responsibilities!) - never just print it out in a notebook. 

For this homework, I want you to create a csv file called myapis.csv and upload it on your google drive in the main folder (My Drive). The code I shared as a skeleton notebook will read it in and your API key will be known in the notebook solong as you call it ```myapis.csv```. 

The csv file should look like

```census,XXXXXXXXXXXXXXXXXXX```

where XXXXXXXXXXXXXXXXXXX is your API key. 

This way a notebook can mount your google drive and ```myAPIkey =  pd.read_csv("myapis.csv")["census"]``` would save the API key in the variable myAPIkey. 
**Dont print it in the notebook!**

Follow the notebook instructions to produce coropleths of DE counties and census tracts
