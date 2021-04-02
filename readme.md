# Unix
# Lab 9

##Part I
file name: part1.pl

Did examples with each of the sections. File IO did not work for some reason.

##Part II
file name: part2.pl

###Question 1
created perl script that printed the same result as echo "Hello World"; date
- created two arrays containing the months and the days of the week
- stored localtime() in a variable and then printed it

###Question 2
stored hostname and uptime in two variables using hostname()  and `uptime -s`

###Question 3
Took two arguments from the user and calculated their sum

##Part III
file name: part3.pl

###Question 2
Used regular expressions to test whether a phone number was valid or not
- tested it with 3 valid and 3 invalid numbers
- also tested with number inputted by user as argument


###Question 3
Created a new user "peter" and used getpwnam("peter") to get all the user's info
- in the member gcos, that we obtained from getpwnam, the full name as well as other information about the user is stored, 
so we store all information from gcos separated by a "," in an array.
- we then take the element at idx 0 from the array to obtain the full name of the user
- for user id : $uid
- for home directory: $dir
- for shell: $shell

###Question 4
Accepts user as an argument and prints their information
- if user does not exist, will not print their information
- if no argument inputted, will print information  of user "peter"


