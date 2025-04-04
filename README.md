# Python-2

**Task 1: Check if a Number is Even or Odd**

Step1: We will be taking input from the user & if the remainder comes zero, it will be an even number or else odd number. We will be using If & Else Statement.

**Code:**

num=int(input('Enter a number: ')) #Here we are taking input from the user to enter a number.

if num % 2 == 0 : # Using IF to find out that number is even or odd.

    print(f"{num} is an even number.") #If the above statment is true, it will print.

else: #If the above statment is false.

    print(f"{num} is a odd number.") #It will print this as odd number.

**Output: Even Number**

![Screenshot 2025-04-04 114119](https://github.com/user-attachments/assets/58b2f923-70da-4472-a022-79b03f8e9429)

**Output: Odd Number**

![Screenshot 2025-04-04 144339](https://github.com/user-attachments/assets/7689851f-e206-4c96-ac61-6c3ef546b956)

**Task 2: Sum of Integers from 1 to 50 Using a Loop**

Step1: We will be using IF function for loop & Sum to add it.

**Code:**

t_sum= 0 #Start will total sum as 0.

for number in range(1,51): #Loop through number from 1 to 50 by using range & for loop.

    t_sum= t_sum + number #It will add the current number with the total sum.

print(f'The sum of numbers from 1 to 50 is: {t_sum}') #Prints the Total Sum.

**Output:**

![Screenshot 2025-04-04 123002](https://github.com/user-attachments/assets/6050177c-dbca-43a1-a144-6102fcf71039)


