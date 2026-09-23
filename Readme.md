## 23/09/2026

## Write a Python program which accepts a sequence of comma separated 4 digit binary numbers as its input and then check whether they are divisible by 5 or not.The numbers that are divisible by 5 are to be printed in a comma separated sequence.
### Example:
    0100,0011,1010,1001
    Then the output should be:
    1010

## Write a Python program that accepts a sentence and calculate the number of letters and digits.
### Suppose the following input is supplied to the program:
    hello world! 123
    Then, the output should be:
    LETTERS 10
    DIGITS 3

## Write a program which can compute the factorial of a given numbers.The results should be printed in a comma-separated sequence on a single line.
###   Suppose the following input is supplied to the 
      program Input:8
      Then, the output should be:40320

## program
~~~
        str=input("Enter str:")
        count_letter=0
        count_digit=0
        for i in str:
          if i.isalpha() :
            count_letter+=1;
          if i.isdigit():
            count_digit+=1;
        print(count_letter)
        print(count_digit)
        
        n=int(input("Enter n:"))
        fact=1
        for i in range(1,n+1):
          fact*=i;
        print(fact)
        
        n1=input("Enter num:").split(",")
        print(n1);
        for i in n1:
          if(int(i,2)%5==0):
            print(i)
        
        import re
        n2=re.split(r'[/*,]',input("Enter num"))
        print(n2);
        for i in n2:
          if(int(i,2)%2==0):
            print(i,end=" ")
~~~

