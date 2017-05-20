# funtion-python
cosecademy unit funtion lesson

# max()
maximum = (1,2,3)

print max(maximum)

#abs() 
#it only takes a single number.
absolute = (-42)

print abs(absolute)

#type()
int :整數
float :浮點數
str :字串

#review:function
def shut_down(s):
    if s == "yes" : 
        return "Shutting down"
    elif s == "no":
        return "Shutdown aborted"
    else:
        return "sorry"
        
#review:module
from math import sqrt
print sqrt(13689)

#review:build in function
def distance_from_zero(a):
    if type(a) == int or type(a) == float:
        return abs(a)
    else :
        return "Nope"
