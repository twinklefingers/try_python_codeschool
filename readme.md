Today I learned about Python:

2016/08/23
Python input lines looks like this:

```
>>>
```
Python does math, in accordance with PEMDAS
Python also can store variable.
Such that
```
>>> us_dollars = 300
>>> exchange_rate = .65
>>> newMoney = us_dollars * exchange_rate
>>> newMoney
```
the above lines of inputed code would yield
```
>>> 195
```
2016/08/24

Python takes strings. Concatenation works the same way that it does is JS.

print to console using print()

use str() when printing things to console to change anything into a string,
such as a number that you want to continue to store as a variable.
```
#use \n for a new line and \t for an indent or tab
```

2016/08/27

find index in an string using [ ]

use
```
print(len(variableName))
```

to find length of a given string in a variable

slices can access parts of strings using a semi colon between the numbers
```
>>> word = Python
>>> word[2:5]
```
this would print out "tho"

shortcuts:
```
>>> word[:2]
```
would print "Py"
```
 >>> word[2:]
 ```
 would print "on"
 ```
 word = 'Python'

first = word[0]
rest = word[1:]
result = rest + '-' + first + 'y'
print(result)
```
print result would yield "ython-Py"

2016/08/30
operators:
```
< less than
<= less than or equal
== equal
>= greater than or equal
> greater than
!= not equal

= variable assignment
True/False booleans
```
conditional statements syntax:
```
rain_speed = 6
if rain_speed < 5:
    print("Just a Scotch mist")
else:
    print("It's a real Cow-quaker out there")
```
If the condition is not met, the code will not run. The else statement offers a programmed answer if the condition is not met.

Anything indented/after the conditional statement will run.
```
rain_speed = 6
if rain_speed < 5:
    print("the rain speed is under 5")    << the indented code block will not run
print("the rain speed is rather fast")    << this line runs
```
Python is crazy particular about 'whitespace'.
PEP 8 Style Guide recommends 4 spaces per indent/tab
