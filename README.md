
<img width="5400" height="2383" alt="Code Karaoke-min" src="https://github.com/user-attachments/assets/cf9296ba-8410-4592-8df0-bac4afd7fdba" />

# Level-3-code-karaoke
Level 3 questions for code karaoke event, there are 2 scenario based  fork and upload in git hub 

# 1st Question :
1.You are building a billing system for a small café.
The café sells:
•	Coffee → ₹60
•	Sandwich → ₹120
•	Cake → ₹80
You need to write a Python program that:
1.	Asks the user what they want to order.
2.	Asks how many of that item they want.
3.	Calculates and displays the total bill.

# Code:
```

menu = {
    "coffee": 60,
    "sandwich": 120,
    "cake": 80
}


item = input()
quantity = int(input())


if item in menu:
    total_bill = menu[item] * quantity
    print("Total Bill =", total_bill)
else:
    print("That item is not on the menu.")
```

# OUTPUT:
<img width="954" height="650" alt="Screenshot 2025-11-08 110805" src="https://github.com/user-attachments/assets/00a09f4f-9740-485a-ad23-b76828ca31a9" />


# Question 2:
2. You’re designing a program for a college portal that evaluates a student’s final grade based on their marks in 3 subjects.
Rules:
•	If the average is 90 or above → Grade A+
•	If the average is 75–89 → Grade A
•	If the average is 60–74 → Grade B
•	If the average is 40–59 → Grade C
•	Below 40 → Fail
The program should:
1.	Take marks for 3 subjects from the user
2.	Calculate the average
3.	Print the average and the grade
________________________________________
# Example Input / Output:
Enter mark for Subject 1: 85
Enter mark for Subject 2: 78
Enter mark for Subject 3: 90
Average = 84.33
Grade = A





# Code:
```
m1 = float(input("Enter mark for Subject 1: "))
m2 = float(input("Enter mark for Subject 2: "))
m3 = float(input("Enter mark for Subject 3: "))

average = (m1 + m2 + m3) / 3


if average >= 90:
    grade = "A+"
elif average >= 75:
    grade = "A"
elif average >= 60:
    grade = "B"
elif average >= 40:
    grade = "C"
else:
    grade = "Fail"

print("Average =", round(average, 2))
print("Grade =", grade)
```

# OUTPUT:
<img width="586" height="824" alt="Screenshot 2025-11-08 111428" src="https://github.com/user-attachments/assets/31b07083-2ddd-41c6-9e93-5d7fcc206c8a" />

