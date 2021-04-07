##Part II 
file name: part2.py

###Question 1: 
Got the hostname using "os.uname()[1]" and uptime using "uptime -s" and printed them

###Question 2:
Got the two arguments entered and calculated their sum by storing the arguments into 
two variables, casting them to int, since they were originally strings, and used them in the sum() function

###Question 3: 
Used regular expressions to test whether a phone number was valid or not
tested it with 3 valid and 3 invalid numbers
also tested with number inputted by user as argument

###Question 4: 
Accepts username as an argument. Throws exception if username is invalid
If valid, 
    get the user's info, store it into variables and print them.
    for the user itself, use: 
    pwd.getpwnam(userInput)
    in the member gecos, that we obtained from getpwnam, the full name as well as other information about the user is stored, so we store all information from gcos separated by a "," in an array.
    we then take the element at idx 0 from the array to obtain the full name of the user

##Part III
