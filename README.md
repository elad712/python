# python
Write a function that receives a positive integer and returns 1 the odd and the number is a prime number) that is divisible by 1 Or to himself alone (otherwise the function returns 0. Write a program that receives a positive integer if a negative number has to print a suitable message, otherwise Use a function to print an appropriate message.

def x(a):
    return a
    
a=int(input('enter any number to chaek is a prime or no'))
if a>1:
    for i in range(2,a):
        if(a%i)==0:
            print(' not prime')
            break
    else:
        print('prime')
