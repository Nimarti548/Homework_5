# 05 Third-Party APIs: Work Day Scheduler

- To start the Work Day Scheduler app I started with the html, I created a container to hold all of the time slots.
- Next I created a row with a full length column in it and put a form inside of it with a text input, submit button, and time stamp.
- Once I had the first time slot all worked out and functioning fine, I copied it and duplicated it for the rest of the time stamps for the business day.
- Using JQuery and Moment.js I set the current date and time for the scheduler.
- I created an array containing the current business hours.
- Using a forEach I created a loop that runs through the times array and checks for any information saved in the Local storage, and checks the current time.
- I then created a conditional with the parameters that if the current time is greater than the time slot, the input line turns gray, if it is the current time then the input turns red to notify user it is the current time slot, and finally it turns all other time slots green to allow for text edits.
- Using the querey selector I set it so it would alternate through all the time slot ids.
- I then created a conditional that allows for the user to save inputed information to the local storage.
- Finally I added an event listener to the forms so if there is information already saved in the local storage it will add it to the text input so the user can retrieve previously saved data.
- To make everything follow the same suit I added a style width of 75 px to all the spans.
