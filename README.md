# LetsUpgrade--AI-ML
#day4
x1 = (5+3j)
x2 = (2+1j)

print(f'Additoin of {x1} and {x2} : ', (x1 + x2))
x1 = (9-2j)
x2 = (5+4j)

print(f'Subtraction of {x1} and {x2} : ', (x1 - x2))
x1 = (5+7j)
x2 = (1+9j)

print(f'Division of {x1} and {x2} : ', (x1 / x2))
x1 = (4+6j)
x2 = (4-5j)

print(f'floor Division of {x1} and {x2} : ', (x1 // x2))
x1 = (4-3j)
x2 = (1+2j)

print(f'Modulpus of {x1} and {x2} : ', (x1 % x2))
x1 = (1-2j)
x2 = (3-5j)

print(f'Multiplication of {x1} and {x2} : ',(x1 * x2))


Range()
range() is a Python In-built function.
It's used to generate a sequence of Numbers.
this function used in Looping system
Syntax

range(start, stop, step)

start: optional-Integer specify from which number to start.Starting from zero(0) by default.
stop: required-Integer specify which number to stop. (Not include)
step: Optional-Integer number for incrementation.
Range()
range() is a Python In-built function.
It's used to generate a sequence of Numbers.
this function used in Looping system
Syntax

range(start, stop, step)

start: optional-Integer specify from which number to start.Starting from zero(0) by default.
stop: required-Integer specify which number to stop. (Not include)
step: Optional-Integer number for incrementation.

y = 111
z = 67
sub = y - z

if sub > 25 :
    print("Multiplication : ", y * z)

else:
    print("Division : ", y / z)


listy = [32,2,191,366,13,56,10,7,15,12]
for num in listy:
    if num%2 == 0:
        print(num**2-2)


listty = [12,43,1,66,1,9,8,2,4,84]
for n in listty:
    if n%2 == 0:
        if n > 7:
            print(n)
