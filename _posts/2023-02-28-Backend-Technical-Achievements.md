---

description: Technical Achievements (backend focus blog)
title: Backend Technical Achievements 
toc: false
comments: true
permalink: /markdown/backendfocus
categories: [Week 24]
layout: post

---


## Overcoming Challenges

- Throughout this project, I had trouble posting data into the database through the api. Furthermore, we started off with one database called "users," which was difficult to manage as we were trying to post and get specific data all from one file. Once we created specific api and database py files for each feature, it as much more organized and allowed us to individually POST and GET through postman. This then allowed us to see the inputted data in the SQLite table. 

![]({{site.baseurl}}/images/SQLITE.png)

![]({{site.baseurl}}/images/ClassDefined.png)

- This code segment shows how the class "Inputworkout" creates a place to store the data inputted into each specific class such as id, uid, exerciseType, etc. The variables defined below the class function allows for individual classes to store data specific to that class. We then take the class defined and call it in the creation of our API. This allows us to create an api and access the data in the database. This is what allows us to post and create as well as get data. 


![]({{site.baseurl}}/images/APIworkout.png)



![]({{site.baseurl}}/images/GarbageCheckError.png)

This is the procedure we used to check for garbage data, which in this case would be if the input is less than two characters. This then creates the 210 error which tells the computer not to add the input into the database. Furthermore, we can use in the frontend to send an alert to the user on the screen.