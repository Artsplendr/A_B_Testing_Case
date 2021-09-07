## Overview
This repository is created to share implemention of A/B Testing with Free Trial Screener for Udacity online educational platform.  
This test is done in the frame of the "A/B Testing" course at Udacity.

At the time of this experiment, Udacity courses had two options on the home page: "start free trial", and "access course materials". 
If a student clicks "start free trial", he/she will be asked to enter credit card information,
and then the student will be enrolled in a free trial for the paid version of the course. 

After 14 days, they will be automatically charged unless they cancel first. 
If the student clicks "access course materials", they will be able to view the videos and take the quizzes for free, 
but they will not receive coaching support or a verified certificate, and they will not submit their final project for feedback.

In the experiment, Udacity tested a change: if the student clicked "start free trial", they were asked how much time they had available to devote to the course. 
If the student indicated 5 or more hours per week, they would be taken through the checkout process as usual. 
If they indicated fewer than 5 hours per week, a message would appear indicating that Udacity courses usually require a greater time commitment
for successful completion, and suggesting that the student might like to access the course materials for free. 
At this point, the student would have the option to continue enrolling in the free trial, or access the course materials for free instead. 

The hypothesis was that this might set clearer expectations for students upfront, thus reducing the number of frustrated students
who left the free trial because they didn't have enough time — without significantly reducing the number of students 
to who successfully complete the course. 

If this hypothesis is true, Udacity could improve the overall student experience and improve coaches' capacity to support students 
who are likely to complete the course.

## Reference:
Udacity course "A/B Testing" at the following link <https://classroom.udacity.com/courses/ud257/>
