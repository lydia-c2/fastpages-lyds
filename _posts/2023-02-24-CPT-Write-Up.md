--- 

description: My CPT
title: College Board Write Up
toc: false
comments: true
permalink: /markdown/CPTwriteup
categories: [Week 24]
layout: post

---


![Workout Plans]({{site.baseurl}}/images/WorkoutInput.png)


### ROW 1
- The overall purpose of this page is to promote community and exercise within the workout community.
- The function of this program is to log and store the exercises, sets, and reps inputted by the users.
- The input is the user's data submitted into the table (the workout, exercise, sets, etc) and the output is the data pulled from the database into the table.

<br>

### ROW 2

![]({{site.baseurl}}/images/ClassDefined.png)
![]({{site.baseurl}}/images/SQLITE.png)

- This code shows the return of the id, uid, exerciseType, sets, and reps data which allows for the program to put user inputted data into the database, seen in the SQLite table.

![]({{site.baseurl}}/images/FetchData.png)

- This shows the fetching of the data as it pulls the data from each class to create a new row on the table. The table displays the data that was inputted into the database through the code previously shown. 

### ROW 3

![]({{site.baseurl}}/images/ClassDefined.png)

- This code segment shows how the class "Inputworkout" creates a place to store the data inputted into the class. The variables defined below the class function allows for individual classes to store data specific to that class.  
- This code manages complexity as it creates a specific class to store the data inputted in an organized manner. This code would not be able to run without a way to store data such as a rest api. This would still allow the program to get and post data, however data must be manually added to the api. 


### ROW 4

![]({{site.baseurl}}/images/CreateForm.png)

This segment of code shows how the code creates the form as well as turning the inputted data into javascript format. The parameter is the data inputted which allows the javascript:create_inputworkout to run. The create function takes the inputted data and turns it into javascript to be stored in the database, which will then be converted to json to be posted to the table. This allows the data inputted to show up on the table. 

### ROW 5

![]({{site.baseurl}}/images/ReadFunction.png)
![]({{site.baseurl}}/images/readInputworkout.png)

The program sequence starts as from the defined _Read class, which a get function to get data from the database to be posted to the frontend. The class uses a for loop to iterate through the data in "Inputworkout," turning the inputted data into json format. The read function defined in the backend is then used as read_inputworkout in the frontend to read through the inputted exercise, set, and rep and check for garbage data. If the data does not meet the conditionals, the data is selected and not appended to the database.


### ROW 6

![]({{site.baseurl}}/images/SQLITE.png)

The program meets this row's requirements through the detection of garbage data. 

1. If non-garbage data is inputted, the data will pass through the conditionals checking if the data is incorrect (garbage). Once it passes these conditions, the inputted data will be stored in the backend file and displayed in the frontend table. The SQLite table above displays the data that met each conditional and is stored in the database

2. If the user does not input an exercise longer than 2 characters, then the conditional for exerciseType in the backend is not met, causing a 210 error. This then notifies the frontend of a 210 error, creating an alert with the message "Exercise is not inputted, please refresh and enter an exercise."
