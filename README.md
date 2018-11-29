# Train-Scheduler
Train Scheduler is an app I created that allows users to add/remove and update fictional train arrivals.

As the user enters the app they're able to see the current list of train schedules that others have added. It also gives them the option to add a train to the list.

The user then is asked for the name of the train, the train's destination, the train's first arrival in military time HH:mm, e.g. if the train's first arrival is at 06:00 AM. Lastly, the user is asked for the train's frequency time in minutes. 

Using MomentJS and Realtime Database from Firebase I was able to calculate the real time and also collect and store users data whenever they add a new train.

The train's frequency, arrival time and how many minutes until the next train's arrival is determined and updated by Moment.JS.

As soon as the user created a new train, there's a submit button available that once it's clicked the new info added by the user will now be seen is the Current Train Schedule table. 

In this new table users will now see the train's name, destination, frequency, the time of the next arrival depending on what time it really is and how many minutes until the next time arrival. Lastly, in this chart the user is also given the chance to either keep the train's data they added or remove it from the list. 

Technologies used: HTML, CSS, Javascript, Bootstrap, Firebase, MomentJS, jQuery.




