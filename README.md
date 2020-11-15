# Date-Method
http://www.michaelogrady.net/college-projects/Javascript-Function-Time-Specific-Display-Content-main/add-content.html

-Simple Javascript function to display specific content at a certain time of the day.

var today = new Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) {
	greeting = 'Good evening!';
	} 
	else if (hourNow > 12) {
	greeting = 'Good afternoon!';
	} 
	else if (hourNow > 0) ; {
	greeting = 'Welcome';
	}
  
  Verify if it is correct by checking the Console
	

Completed during 2016-2018 in Bsc Information Systems
=================================================================================================================================================================================
