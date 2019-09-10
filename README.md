# Lab2

In Lab2 I learned about using Pi in Python, Math Modules, The Archimedes Approach, Accumulator Approximations, Computing averages, computing sums and the Monte Carlo Simulation.

5.


6. 
x = 0

for First100EvenSum in range(0,201,2):
    x = x + First100EvenSum
    print(x)

y = 0

for First50OddSum in range(1,100,2):
    y = y +First50OddSum
    print(y)

total = 0
length = 0
for i in range(1, 200, 2):
    total += i
    length += 1

print(total / length)

7. 
x = int(input("Enter a number between 1 and 10: "))
if 0 < x <11:
    print("True")
else:
    print("False")
    
Enter a number between 1 and 10: 1
True
Enter a number between 1 and 10: 5
True
Enter a number between 1 and 10: 9
True
Enter a number between 1 and 10: 10
True
Enter a number between 1 and 10: 12
False

8.
score = int(input("Enter your score: "))
GRADEPOINT = int
if score >= 90:
    GRADEPOINT = 4
elif 80 <= score <= 89:
    print("GRADEPOINT = 3")
    print(score)
elif 70 <= score <= 79:
    print("GRADEPOINT = 2")
    print(score)
elif 60 <= score <= 69:
    print("GRADEPOINT = 1")
    print(score)
elif score > 60:
    print("GRADEPOINT = 0")
    print(score)
    
