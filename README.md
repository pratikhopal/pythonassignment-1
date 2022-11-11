# pythonassignment-1

Q1. Why do we call Python as a general purpose and high-level programming language?
Ans: Python is called general purpose language because it can be used to create software in wide variety of applications across hardware configurations and operating systems. It is also considered as high-level programming language as it is considered easy for humans to understand.



Q2. Why is Python called a dynamically typed language?
Ans: Because we don’t have to declare data type of the variable and it is determined during the runtime.



Q3. List some pros and cons of Python programming language?
Ans: Pros of python language are
1)	Easy to understand and learn
2)	Scalable
3)	Used in machine learning
Cons of python language are
	1)Dynamically typed
	2)slower than compiled languages
	3)Inefficient memory usage.
  
  
  
Q4. In what all domains can we use Python?
Ans: We can use python in web development, data science, data engineering and Machine Learning domains among others.



Q5. What are variable and how can we declare them?
Ans: Python has no command to create a variable, a variable a reference or a pointer to an object.



Q6. How can we take an input from the user in Python?
Ans: We can take input from the user using the input() function.



Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans: By default it is a string.



Q8. What is type casting?
Ans: Type casting is the method to convert a data type into another particular data type.



Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans: Yes, using the spilt() function we can get multiple inputs.



Q10. What are keywords?
Ans: Python keyword are reserved keywords with special uses and meaning, special purpose. They can’t be used for other purposes.



Q11. Can we use keywords as a variable? Support your answer with reason.
Ans: No we cannot, as keywords are reserved and the compiler might get confused and won’t accept those words.



Q12. What is indentation? What's the use of indentation in Python?
Ans: Indentation in python are whitespaces before any statement in python. Used to create a space to identify a particular code block. 



Q13. How can we throw some output in Python?
Ans: we can output in python using print().



Q14. What are operators in Python?
Ans: Operators in python are special symbols that designate that some sort of computation should be performed.



Q15. What is difference between / and // operators?
Ans: // return integer while the / returns a float value.



Q16. Write a code that gives following as an output.
Ans: print('iNeuron'*4)



Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans:
a=int(input())
if a%2 == 0:
    print("even")
else:
    print("odd")
    
    

Q18. What are Boolean operator?
Ans: Boolean operator are ‘and’, ‘or’ and ‘not’ and evaluate the true or false of the operand.




Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
Ans: 
1
0
False
1




Q20. What are conditional statements in Python?
Ans: Conditional statements are used to determine whether the code block would be executed or not.




Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans: if is used to check if the condition is satisfied or not. Elif is a optional alternative to the if the condition which is checked if the ‘if’ condition didn’t work. ‘Else’ is used to execute the code block that has pre checked all other conditions.




Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans:
age = int(input("Enter your age"))
if age >=18:
    print("I can Vote")
else:
    print("I Can't Vote")



Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for i in numbers:
    if i%2==0:
        sum=sum+i
print(sum)



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans: 
a=int(input("enter the first number"))
b=int(input("enter the second number"))
c=int(input("enter the third number"))
if a > b and a > c:
    print(a)
elif b>a and b>c:
    print(b)
else:
    print(c) 




Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans:

numbers = [12,75,150,180,145,525,50]
for i in numbers:
    if i>500:
        break
    if i%5==0:
        if i<150:
            print(i) 

