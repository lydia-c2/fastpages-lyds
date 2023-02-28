---

description: Technical Achievements (backend focus blog)
title: Backend Technical Achievements 
toc: false
comments: true
permalink: /markdown/backendfocus
categories: [Week 24]
layout: post

---


## Overcoming Challenges and How it Works

- Throughout this project, I had trouble posting data into the database through the api. Furthermore, we started off with one database called "users," which was difficult to manage as we were trying to post and get specific data all from one file. Once we created specific api and database py files for each feature, it as much more organized and allowed us to individually POST and GET through postman. This then allowed us to see the inputted data in the SQLite table. 

![]({{site.baseurl}}/images/SQLITE.png)

![]({{site.baseurl}}/images/ClassDefined.png)

- This code segment shows how the class "Inputworkout" creates a place to store the data inputted into each specific class such as id, uid, exerciseType, etc. The variables defined below the class function allows for individual classes to store data specific to that class. We then take the class defined and call it in the creation of our API. This allows us to create an api and access the data in the database. This is what allows us to post and create as well as get data. 


![]({{site.baseurl}}/images/APIworkout.png)



![]({{site.baseurl}}/images/GarbageCheckError.png)

This is the procedure we used to check for garbage data, which in this case would be if the input is less than two characters. This then creates the 210 error which tells the computer not to add the input into the database. Furthermore, we can use in the frontend to send an alert to the user on the screen.

**Issues we had**

With the garbage data check, it took us a while to figure out how to get the conditionals to actually work. When we tried to make it so the input "!== str" the conditional read integers as strings too. I combated this issue by making sure that input could only be integers (+ and - button on the side of the form). For the exerciseType, we made the conditional check if input was < or > 2 characters. I then  defined this as a 210 error, which I connected to the frontend with another conditional which blocked the posting if a 210 error occured. 


## Timeline

- When we first started the project, we created one api and database for every feature (user.py and users.py). We also tried to do this only on the frontend and call the api and data from frontend file to file. However, this did not work. 
- We created each class and api specifically for each feature; Inspiration, ISPE, Inputworkout, and workouts. Originally, they were all in the same file, but we split them up and created a new py file for each one.
- When we created our flask page, we moved all the database and api files into the teambaddieflask repo. 
- From there, we had to troubleshoot the errors that came up when using Postman. At this point, we ran localhost to localhost to allow us to continue to edit the backend (we also had not deployed). 
- We continued to add to our own features, and I added the classes within my file to create places for my data from the frontend to be stored. Once postman started working, we had to troubleshoot why there was a creation error in the table. We eventually figured out this was because there was no id or uid input, which was defined as "required." 
- We fixed this as defining uid as "datetime" in the backend api
- Finally, we fixed our garbage data check.
- Then, we rebuilt our deployed page through aws.