Description of the problem
    - I am trying to evolve a program that outputs the result 100 by putting + or - or nothing between the numbers 1,2,…,9
    - I chose this problem because I felt like it is interseting to evolve and would be easy to succeed (spoiler it is not as easy as it seems). 

Setup 

    - I have also added the integers 0-9 into the instruction list so they can be used.  I have also added the functions integer_+ , integer_- and integer_combine to add, subtract and combine two integers. I created the function integer_combine because there is no function that combines two integers in propel. Integer_combine works by taking two integers and checks if the second number is negative. if it is, the function will change the absolute value of that number. then it changes the two numbers into a sting, concatinates them, change them back to integer again and returns the number combined number.  

    - To check if my output is correct i have created the function that takes the correct output and the actual output and gives the absolute value of the difference. which gives me the error. 


Results 

    - My program ended up evolving the solution to my problem but not fully. To elaborate, My problem was suppose to take numbers 0-9 and use them each once to get the solution 100. However, my program sometimes takes the numbers multiple times and it also doesn't use all the numbers. to tackle that i have tried implimenting a way to not compute the expression until the end to count how many occurances there are for the numbers. for example if we get the expression (1+2-3+56), I can count the occureances of the numbers 1, 2, 3, 5, and 6 but that ended up breaking my integer_combine function. I also tried passing the number 0-9 as strings and concatinate them into a string math expression so that it can be easier to count the occurances of the numbers. through the help of Nic, i was able to make the program run but it still didn't solve the problem of not using all the numbers and using them multiple times. (My string implemenation is in the branch string) 

