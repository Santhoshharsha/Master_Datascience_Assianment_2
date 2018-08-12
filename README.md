# Master_Datascience_Assianment_2
Master_Datascience_Assianment_2
# 1. Write a program which accepts a sequence of comma-separated numbers from console and generate a list.
values = input("Input some comma seprated numbers : ")
list = values.split(",")
print('List : ',list)
#1,2,3,4

# 2. Create the below pattern using nested for loop in Python.
n=5;
for i in range(n):
    for j in range(i):
        print ('* ', end="")
    print('')

for i in range(n,0,-1):
    for j in range(i):
        print('* ', end="")
    print('')
    
    
 # 3. Write a Python program to reverse a word after accepting the input from the user.
word = input("Input a word to reverse: ")

for char in range(len(word) - 1, -1, -1):
  print(word[char], end="")
print("\n")
# SANTHOSH.B

# 4. Write a Python Program to print the given string in the format specified in the sample output. 
 #WE, THE PEOPLE OF INDIA, having solemnly resolved to constitute India into a SOVEREIGN, SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC and to secure to all its citizens Sample Output:
#WE, THE PEOPLE OF INDIA,
#    having solemnly resolved to constitute India into a SOVEREIGN, !
#        SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC
#        and to secure to all its citizens
print("WE, THE PEOPLE OF INDIA, \n\t having solemnly resolved to constitute India into a SOVEREIGN,! \n\t\t SOCIALIST, SECULAR,
      DEMOCRATIC REPUBLIC \n\t\t  and to secure to all its citizens")






