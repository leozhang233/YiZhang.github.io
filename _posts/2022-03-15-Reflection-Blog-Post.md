---
layout: post
title: Reflection Blog Post
---

In this Blog Post, as a group, we will write a brief reflection on the experience of completing the project.

## Project Group(BGS) member:
- Jiaqi Li
- Shurui Wang
- Yi Zhang

## Project Overview

Our project will try to find an answer to the following question:
**Given permission of camera access, what information can we obtain from facial recognition and how can we potentially make use of that information?**
Overall, our project focus on facial emotion recognition and recommendations based on the detected emotion. More specifically, we will train a model that is able to classify the emotion of human faces detected in an uploaded photo and make the whole process interactive through implementation on our webpage.

Here is our project [Github Link](https://github.com/leozhang233/PIC16B-PROJECT). You can find detailed instructions on how to run our Webapp and what to expect here.

## Reflection

### Overall, what did you achieve in your project? 

This project has been an exploratory experience for all of us. We came up with a proposal that none of us knew how to make it at the beginning of this quarter, but eventually achieved a wonderful local Webapp that none of us ever thought we were able to. Our Webapp has met all our expectations in our proposal, and it is 100% successful. We have built a web app that contains a machine learning model to do emotion detection using facial recognition. We will need the user to upload a selfie themselves, and the Webapp will automatically detect the user's face with an OpenCV model.  With just one selfie uploaded by the user, we will be able to present different recommendations to the user according to the detected emotion.

### What are two aspects of your project that you are especially proud of?

The first thing we are proud of is the OpenCV model. We were planned to ask the user to upload a selfie meeting some specific requirements in the beginning. However, we decided to go deeper than this. What about letting the user upload a photo containing human faces, and letting the Webapp crop the image section needed by itself? Sounds cool. This is a brand new topic for us, and none of us knew how to do it with Python. After doing some research online, we have made this happen with OpenCV. 

The second thing that we are also really proud of is our front-end. We managed to build a functioning Webapp from scratch to integrate what we’ve accomplished in our project. It was really challenging for us to add the model to the Webapp, and fix the syntax errors with the message bank. The only pity is after we integrate everything to Heroku, it failed to compile an online Webapp since our model is too large for a free account.  Although we have to keep our Webapp local, we have added everything we could think about and everything we could make work to our Webapp. We are very proud that we have done our best in building this Webapp.

### What are two things you would suggest doing to further improve your project? (You are not responsible for doing those things.)

The first thing we could improve is our Website design. Our Website looks very simple now, and it is basically very similar to the in-class flask example. We didn't go very deep into CSS styling, and we could have made large modifications to our Webapp appearance by adding new objects and new functions. We could also improve it by using some fancy Web templates like bootstrap. If we have more time, we would definitely figure it out.

The second thing that we could improve is our recommendation system. Our Webapp can only recommend a quote or a Youtube video to the user according to the mood in the photo. If we want to make this function more advanced, we could add more data to our recommendation database. For example, we could add more recommendation areas for the user to choose from, such as recommendations for shopping, music, games, movies, etc. We could also ask the user for feedback about our recommendation and improve it accordingly. It might be a bit beyond our course, but it is worth trying.

### How does what you achieved compare to what you set out to do in your proposal? (if you didn't complete everything in your proposal, that's fine!)

Compared to what we set out to do in our proposal, I think we not only fully completed every everything but also introduced more features to improve our webapp's functionality and performance. For our planned deliverable, we successfully created an emotion classification model that achieved a higher accuracy than our expected baseline. In addition, the webapp we created can provide several choices for the users once their received our predicted result. Based on the users' selection, our webapp can send a recommendation of either a quote or a video corresponding our predicted emotion. Furthermore, to develop and improve our webapp's functionality and performance, we did something extra, such as creating a facial extraction feature in the upload section, and providing a feedback textbox to the users in order to collect information for future model improvement.

### What are three things you learned from the experience of completing your project? Data analysis techniques? Python packages? Git + GitHub? Etc? 

1.	I learned how to use `Tensorflow` and `OpenCV` to perform image classification. With the facial image extracted by the OpenCV, we can use it to predict one of the emotional categories, such as happy, unhappy, neutral, and so forth through our Tensorflow model trainned by transfer learning with InceptionV3.

2. I learned how to use `webscraping` to access and consolidate a range of disparate data sources into a new, publicly available data set. With one keyword provided, I can use it to scrape not only a list of quotes related to that keyword from one of the largest quotation website, Brainyquote, but also a list of weblinks related to that keyword as well from YouTube.

3. I learned how to use write an interactive `webapp` to visualize different kinds of dynamical processes, such as creating/redirect a dynamic route, capturing multiple URL variables, storing data from the users into local files, and making various types of HTML form like text field, radio object, submit button, etc.

## How will your experience completing this project will help you in your future studies or career?

After completing this project, I think I can apply this valuable experience for my future studies and career. For example, With the Modules and Packages learned from this project, I can study more content behind them for gaining data science and programming knowledge. I can continue to work on an improvement of the project with my peers for potenital product development. I can also write all these skill set learned from this project into my resume for academy and workplace in order to making me an attractive and competitive candidate.
