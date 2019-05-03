# CampusCarRental
This was a campus car rental system. Users can rent cars to use for errands or pleasure.
System has a fleet of 9 cars.
Arlington Auto club members get a 10% discount on all rentals. Tax is 8.25%. Weekends are Sa & Su.
Partial day rentals are charged a full day. Rentals are 24-hour periods - if any portion of that 24-hour period is a weekend rate the entire day is charged weekend. For example, a Car rental that starts on Thursday at 6pm and returns on Sat 10am would be charged one Weekday rental and one Weekend day rental. A week rental is 7-days.

Three different kinds of users for the system:
1.	Rental manager 
a.	creates own profile
b.	views calendar of all cars rented
c.	views details of a specific rental
d.	views available cars for a given date/time
e.	deletes a rental
f.	update his own profile
g.	adds a new car (the rental manager can add a new vehicle with the attributes specified in the first table above).


2.	User
a.	creates own profile
b.	requests rental - items, number of occupants, date, time, duration, extras
i.	The software only shows available cars that meet the minimum occupant capacities
ii.	each car shows estimated prices based on selections.
iii.	Users less than 18 are not allowed to rent. Users less than 25 must pay a $250 deposit which is added to the rental bill.
c.	view my reserved rentals
d.	cancel my reserved rentals
e.	confirm/pay for my reserved rentals
f.	update profile


3.	Admin
a.	creates own profile
b.	edit user profile
c.	change user roles
d.	revoke renter (renter still exists in system but cannot rent a car)

Project uses Java, Eclipse, Tomcat and MySQL. For testing JUnit and Selenium is used.

