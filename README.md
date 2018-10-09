# blinkingTextDemo
Dynamic infinite blinking text slider with nth number of div 


# Requirement
Text blinking slider which work Dynamically for infinite time 
User just have to add a new div structure and edit text details from it and it will dynamically reflact in slider

# Solution
To resolve this situation we call blinkSection() for every 5 seconds and in thes function we fadeIn and fadeOut every div.
After that we added 'done' class in that.  

while the total length of section class div and total length of done class div are equal we just follow the previous process and then we clear all done class and again show the first section div.

So, it will continue from the first section div class and work same as above again. 
