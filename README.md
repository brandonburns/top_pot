# top_pot

This code starts out by creating a constructor function that defines 
common properties for all Top Pot locations. 

I then define a function that takes a random amount of foot traffic 
based off of the averages in each store. I then create a new 
function that uses the previous one, and finds how many donuts
per any random hour are needed for that particular location.

After creating an instance of the constructor function for each 
location, I created a report function that uses a for-loop to 
assign a different random amount of donuts needed for each 
hour that that particular location is open. 


There were no collaborators on the assignment, but I did seek 
assistance from the instructors at times to help de-bug my
code. 

I referenced for-loops I had made in codecademy to help me better 
understand how I need to write the for-loop for this code.


Below is a print out of both:

- The number of donuts needed per hour in each store (5 sets of 11 lines of code)
- The total number of donuts needed per day at each location


Here is the code for each hour 

 The downtown location needs 37.6496243044734 for the 1 hour.
top_pot.html:24 The downtown location needs 37.9364674590528 for the 2 hour.
top_pot.html:24 The downtown location needs 20.54093032851815 for the 3 hour.
top_pot.html:24 The downtown location needs 4.045788915455342 for the 4 hour.
top_pot.html:24 The downtown location needs 31.919358232617377 for the 5 hour.
top_pot.html:24 The downtown location needs 40.42747858315706 for the 6 hour.
top_pot.html:24 The downtown location needs 6.148756486922503 for the 7 hour.
top_pot.html:24 The downtown location needs 47.852431658282875 for the 8 hour.
top_pot.html:24 The downtown location needs 38.188957852870224 for the 9 hour.
top_pot.html:24 The downtown location needs 37.55505088865757 for the 10 hour.
top_pot.html:24 The downtown location needs 0.7867843709886074 for the 11 hour.
top_pot.html:24 The Capitol Hill location needs 8.581752003729344 for the 1 hour.
top_pot.html:24 The Capitol Hill location needs 3.588439819961786 for the 2 hour.
top_pot.html:24 The Capitol Hill location needs 23.343790923804043 for the 3 hour.
top_pot.html:24 The Capitol Hill location needs 34.27078494764864 for the 4 hour.
top_pot.html:24 The Capitol Hill location needs 16.885278957523404 for the 5 hour.
top_pot.html:24 The Capitol Hill location needs 2.0726385382935404 for the 6 hour.
top_pot.html:24 The Capitol Hill location needs 5.720971864275635 for the 7 hour.
top_pot.html:24 The Capitol Hill location needs 35.71968244817108 for the 8 hour.
top_pot.html:24 The Capitol Hill location needs 31.315291012264787 for the 9 hour.
top_pot.html:24 The Capitol Hill location needs 17.732550471648572 for the 10 hour.
top_pot.html:24 The Capitol Hill location needs 35.31823527775705 for the 11 hour.
top_pot.html:24 The South Lake Union location needs 2.7711044817231594 for the 1 hour.
top_pot.html:24 The South Lake Union location needs 6.123470621136949 for the 2 hour.
top_pot.html:24 The South Lake Union location needs 2.3724752170499412 for the 3 hour.
top_pot.html:24 The South Lake Union location needs 5.154821469867603 for the 4 hour.
top_pot.html:24 The South Lake Union location needs 4.686623520869762 for the 5 hour.
top_pot.html:24 The South Lake Union location needs 18.867849964136255 for the 6 hour.
top_pot.html:24 The South Lake Union location needs 10.933855605963618 for the 7 hour.
top_pot.html:24 The South Lake Union location needs 0.6375467816367746 for the 8 hour.
top_pot.html:24 The South Lake Union location needs 15.89715015767142 for the 9 hour.
top_pot.html:24 The South Lake Union location needs 10.310301016503946 for the 10 hour.
top_pot.html:24 The South Lake Union location needs 8.393635451747105 for the 11 hour.
top_pot.html:24 The Wedgewood location needs 8.289410609006882 for the 1 hour.
top_pot.html:24 The Wedgewood location needs 9.297581915929914 for the 2 hour.
top_pot.html:24 The Wedgewood location needs 0.6851110087707639 for the 3 hour.
top_pot.html:24 The Wedgewood location needs 7.207551689073444 for the 4 hour.
top_pot.html:24 The Wedgewood location needs 4.61949269771576 for the 5 hour.
top_pot.html:24 The Wedgewood location needs 7.6821060927584774 for the 6 hour.
top_pot.html:24 The Wedgewood location needs 2.253636878170073 for the 7 hour.
top_pot.html:24 The Wedgewood location needs 11.61853620428592 for the 8 hour.
top_pot.html:24 The Wedgewood location needs 3.4560240257531407 for the 9 hour.
top_pot.html:24 The Wedgewood location needs 1.1510670829564331 for the 10 hour.
top_pot.html:24 The Wedgewood location needs 9.513379944674671 for the 11 hour.
top_pot.html:24 The Ballard location needs 30.00779395112302 for the 1 hour.
top_pot.html:24 The Ballard location needs 37.99373474174179 for the 2 hour.
top_pot.html:24 The Ballard location needs 35.89914143648464 for the 3 hour.
top_pot.html:24 The Ballard location needs 29.28819412136916 for the 4 hour.
top_pot.html:24 The Ballard location needs 1.7181021549459548 for the 5 hour.
top_pot.html:24 The Ballard location needs 18.276142708766272 for the 6 hour.
top_pot.html:24 The Ballard location needs 29.225053238491526 for the 7 hour.
top_pot.html:24 The Ballard location needs 25.454312480329534 for the 8 hour.
top_pot.html:24 The Ballard location needs 34.0182588918088 for the 9 hour.
top_pot.html:24 The Ballard location needs 48.05650772205088 for the 10 hour.
top_pot.html:24 The Ballard location needs 11.839466800955124 for the 11 hour.


Here is the code for the total number of donuts for each day per location 

top_pot.html:34 The downtown location needs 348.811400951445 per day 
top_pot.html:34 The Capitol Hill location needs 241.3112694896758 per day 
top_pot.html:34 The South Lake Union location needs 101.98070384440942 per day 
top_pot.html:34 The Wedgewood location needs 72.09884150158614 per day 
top_pot.html:34 The Ballard location needs 194.39302976219443 per day 