# Python-project
This is a python code whose topic is "Student Marks and Grade Calculator".

print("STUDENT MARKS AND GRADE CALCULATOR")

name = input("Enter student name: ")

m1 = float(input("Enter marks in English: "))
m2 = float(input("Enter marks in Maths: "))
m3 = float(input("Enter marks in Science: "))
m4 = float(input("Enter marks in Computer: "))
m5 = float(input("Enter marks in Hindi: "))

total = m1 + m2 + m3 + m4 + m5
percentage = total / 5

print("\nStudent Name:", name)
print("Total Marks:", total, "/ 500")
print("Percentage:", percentage, "%")

if percentage >= 90:
    print("Grade: A+")
elif percentage >= 80:
    print("Grade: A")
elif percentage >= 70:
    print("Grade: B")
elif percentage >= 60:
    print("Grade: C")
elif percentage >= 40:
    print("Grade: D")
else:
    print("Grade: Fail")
