# Evaluation
### What Questions Are You Asking? 

The primary objective of the evaluation phase of our application is to answer the following questions

#### Front-end evaluation
-	Is the source and destination entered by the user recognized by the application?
-	Are the routes displayed correctly?
-	Are the events along the way displayed and notified to the user?
-	Can the user view all the events on a particular day?
-	Are the event details (Event name, start-time and end-time) displayed for every event?
-	Are the alternate routes (if available), feasible to suggest?
	
### Experimental Methods

**Experiment 1** 

Overview 

We will be checking the delay times due to traffic from a source and destination, and the route passes through a venue which hosts an event at that time. This is a desk experiment, where all the team members will be using google maps to check the time taken to commute.

#### Design

For every event, we have an estimated pre-start time (a time estimation that traffic increases before the event) and post-end time (a time estimation that traffic is more after the event). In this experiment, we will record the time taken to commute between a source and destination from the pre-start time to post-end time. The time taken will be observed every 10 mins and the time is recorded. Each team member will have a source and destination of their own choosing, making sure the route passes along an event. This experiment will be conducted for every event on a particular day by the team starting from 10/07/18.

#### Data Collection 

The data collected is
-	Distance between the source and destination (Kilometers)
-	Time taken to commute the distance (Minutes)
-	Time delay during the commute (the difference between the quickest and slowest times)
-	Here is an example of the data recorded

![Data]( nhriday.github.io/evaluation/Data.png )
 
#### Selected Subjects 

For this experiment, we do not intend to involve people to evaluate the application as this is a desk experiment. We ourselves will be carrying out the above-mentioned process.

#### Data Analysis 

As mentioned in ‘Data Collection’, we will be recording the time taken to commute every 10 min and entering the values in an excel file. We record the delay due to traffic by calculating the difference between the quickest and slowest commute times. This analysis gives us an estimate of the delay times due to traffic for every type of event ranging from a capacity of 1000 to 30000. This helps us notifying the user about the traffic conditions along the route and whether suggesting an alternate route is feasible.

#### Practical Setup 

The experiment will be an online experiment. Certain instructions are to be followed strictly. The team members make sure that the google maps page with the route and the time is refreshed every 10 mins. The time is noted for every iteration. The experiment can be conducted anywhere with a laptop and an internet connection.

### Conclusions 
What can you conclude after running the experiment(s) described (e.g., will you learn anything useful about the quality of your solution)? what challenges do you expect in running the experiment(s)? …
From the experiment we can make a very good estimation on the delay times of the commute due to traffic. From this data collected, we can conclude if the feature of providing alternate routes, displaying the events on the map and notifying the user of events along the route and the traffic condition is feasible enough and serves the purpose of the aim of the project defined.

### References
**Google Maps**



