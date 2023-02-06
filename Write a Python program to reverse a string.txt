#Write a Python program to reverse a string.

#Sample String : "1234abcd"
#Expected Output : "dcba4321"

def reverse_string(str):  
    str1 = ""   
    for i in str:  
        str1 = i + str1  
    return str1    

str = input ("Enter a string :")       
print("The original string is : ",str)  
print("The reverse string is :",reverse_string(str))