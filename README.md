# What is this about?
This task meant to measure needed job skills, and it is a part of the hiring evaluation process. we expect you to be comfortable and enjoying while doing the task.

## Job skills
* Attention to details.
* Thinking, problem solving and decision-making.
* Knowledge of different technologies.
* Ability to learn and adapt to changes.
* Quality of code structure.

# Task Details
 The objective is to develop an 'Events Management' module that will assist the back-end users in managing events that the end-users will browse.
 
## Event Management main features:
```
Event Attributes:
 - Title   
 - Image  
 - Description  
 - Start and end date and time (The end date and time must not exceed the start date)  
 - Category of event   
 - Event country  
 - Event city (The city field filled in automatically when the user selected a country)
``` 

* Back-end
    * CRUD to manage events.
    * Show list of attendees for each event.
    * The module has a configuration page with:
        * The option to show or hide past events.
        * A number of events to list on the listing page.
    * Audit log when the user changes the module configurations.
    * It should automatically send emails to attendees 2 hours before the start time of the event with event details. These emails should be queued.

* Front-end
    * Page to list published events.
    * Details page for events.
    * End-users click attend on preferred event.

* APIs
    * List events filtered by start date and end date, sorted by the closest start date and time in the date range specified.

# Task Deliverables
1. Git repo has:
    * Code implementing the above features.
    * Code Documentation.
    * README file to install the proper steps.
    * Task rate on a scale of 1 to 5.

# Prerequisites
#### Symfony => 6.0
* PHP => 8.0
* MySQL => 8.0

# Note
Using docker is a must.

##### Thank you, can't wait to join us.
