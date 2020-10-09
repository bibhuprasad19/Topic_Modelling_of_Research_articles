# Topic Modelling of Research Articles

![GitHub Logo](https://datahack-prod.s3.ap-south-1.amazonaws.com/__sized__/contest_cover/jantahack_i-day-thumbnail-1200x1200-90.jpg)


As the world says it 'Data is the new oil', the phrase speaks for itself. The modern world has huge number of scientific articles stored in the web that sometimes it becomes really difficult to find relevant items.Tagging and classifying research articles would to a large extent ease the process.

Given the abstract and topic of the article we intend to predict the topic of the article.

Note that a research article can possibly have more than 1 topic. The research article abstracts and titles are sourced from the following 6 topics:

1- Computer Science

2- Mathematics

3- Physics

4- Chemistry

5- Quantiative Finance

6- Quantitaive Biology

Download Dataset from :

datahack.analyticsvidhya.com/contest/janatahack-independence-day-2020-ml-hackathon/download/train-file



**APPROACH**

To classify multiple classes I used the Machine learning approach of TF-IDF vectorizer. To train the model a very simple approach was adopted where I used six different Logistic Regression for six topics. The main reason for taking such an approsch is that a single article could belong to more than one topic. I got a F1-score of 79.6.
