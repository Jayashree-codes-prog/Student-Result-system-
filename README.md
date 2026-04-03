# Student-Result-system-
My second Python project - a  student result medium
name = input("Student name : ")
roll = input("Roll number : ")

sub1 = float(input("Bangla marks : "))
sub2 = float(input("English marks : "))
sub3 = float(input("Math marks : "))
sub4 = float(input("Physics marks : "))
sub5 = float(input("Chemistry marks : "))

total = sub1 + sub2 + sub3 + sub4 + sub5
percentage = total / 5

print("\n----- STUDENT RESULT -----")
print("Name:", name)
print("Roll:", roll)
print("Total Marks =", total)
print("Percentage =", percentage)

if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B"
elif percentage >= 60:
    grade = "C"
elif percentage >= 50:
    grade = "D"
else:
    grade = "Fail"

print("Grade:", grade)

if sub1 >= 33 and sub2 >= 33 and sub3 >= 33 and sub4 >= 33 and sub5 >= 33:
    print("Result: PASS ✅")
else:
    print("Result: FAIL ❌")
