# Assignment-2
Asignment-2 Python2
#this is question and asnwer for assignment-2 forPython-2 training session .
# question and Answer are in the Code tab but the result is share as a link to an uploaded screenshot as per instruction.

Question 1. Write a program which acceptsa sequence of comma-separated numbers from console and generate a list.
Answer 1. 
my_list=input('Please input comma-separated numbers:',)
final_list=my_list.split(',')
print(final_list)


Question 2 : Create the below pattern using nested for loop in Python .
*
**
***
****
*****
****
***
**
*
answer 2 : 
for i in range(1,6):
    print('*'*i)
for j in range(4,0,-1):
    print('*'*j)
    
Question # 3 . Write a Program to reverse a word after accepting the input from the user 

Answer # 3. 
s=input('What is your name',)
print(s[::-1])

Question # 4 . Write a Python Program to print the given string in the format specified in the sample

Answer #4.
a="WE, THE PEOPLE OF INDIA,"
b="having solemnly resolved to constitute India into a SOVEREIGN, !"
c="SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC"
d="and to secure to all its citizens"
print(a,"\n\t", b,"\n\t\t", c,"\n\t\t", d)
