# BASICS OF PYTHON


```python
print('hello word')
```

    hello word
    

# Veriable


```python
student = 'sam'
```


```python
student
```




    'sam'




```python
student = 'matt'
```


```python
student
```




    'matt'



# Data type


```python
a1 = 10
a1
```




    10




```python
type(a1)
```




    int




```python
a1 = 3.14
a1
```




    3.14




```python
type(a1)
```




    float




```python
a1 = True
a1
```




    True




```python
type(a1)
```




    bool




```python
a1 = 'hello word'
a1
```




    'hello word'




```python
type(a1)
```




    str




```python
a1 = 3+4j
a1
```




    (3+4j)




```python
type(a1)
```




    complex



# OPERATORS
# Arithemetric operators

```python
# +,-,*,/
```


```python
a=20
b=30
```


```python
a,b
```




    (20, 30)




```python
a+b
```




    50




```python
a-b
```




    -10




```python
b-a
```




    10




```python
a*b
```




    600




```python
a/b
```




    0.6666666666666666


#Relational operators

```python
# <,>,==,!=
```


```python
a=50
b=70
```


```python
a<b
```




    True




```python
a>b
```




    False




```python
a==b
```




    False




```python
a!=b
```




    True


# Logical operators

```python
# &,|
```


```python
a=True
b=False
```


```python
a & b
```




    False




```python
a & a
```




    True




```python
b & a
```




    False




```python
b & b
```




    False




```python
a | b
```




    True




```python
a | a
```




    True




```python
b | a
```




    True




```python
b | b
```




    False



# python tokens
#keywods

```python
#True, class, if,yield, while, false, finally, is, return, try, none, continue, for, lambda, try, def, from, nonlocal, while, and, del, global, not, with, as, eelif, if, or

```
# identifiers

```python
Student = 'sartha'
```


```python
student ='dinesh'
```


```python
Student
```




    'sartha'




```python
student
```




    'dinesh'


#literals - Do not change 

```python
a ='hello'
```


```python
a
```




    'hello'




```python
#strings
```


```python
str1 ="this is my first string"
```


```python
str1
```




    'this is my first string'




```python
str2 ="this is my second string"
```


```python
str2
```




    'this is my second string'




```python
str3 = '''
this
is 
my 
third
string
'''
```


```python
str3
```




    '\nthis\nis \nmy \nthird\nstring\n\n'




```python
my_string ="My name OM"
```


```python
my_string
```




    'My name OM'




```python
my_string[0]
```




    'M'




```python
my_string[-2]
```




    'O'




```python
my_string[4:10]
```




    'ame OM'




```python
len(my_string)
```




    10


#string function

```python
my_string.lower()
```




    'my name om'




```python
my_string.upper()
```




    'MY NAME OM'




```python
my_string.replace('M','P')
```




    'Py name OP'




```python
my_string.count('name')
```




    1




```python
ste_new ='sparta sparta sparta 2 2 2 22 2 2 2 2 2 22'
```


```python
ste_new
```




    'sparta sparta sparta 2 2 2 22 2 2 2 2 2 22'




```python
ste_new.count('2')
```




    12




```python
s1 ='this iss om'
```


```python
s1
```




    'this iss om'




```python
s1.find('om')
```




    9




```python
fruit ='I like banna,apple,mango'
fruit
```




    'I like banna,apple,mango'




```python
fruit.split(',')
```




    ['I like banna', 'apple', 'mango']



# Data-structure in python


```python
# 1Tuple 2.list 3.Dictionary 4.Set
```

# Tuple in python


```python
tup1 =(1,True,'OM',2.34,2+4j)
```


```python
tup1
```




    (1, True, 'OM', 2.34, (2+4j))




```python
tup1[0]
```




    1




```python
tup1[2]
```




    'OM'




```python
tup1[-1]
```




    (2+4j)




```python
tup1[0:4]
```




    (1, True, 'OM', 2.34)




```python
type(tup1)
```




    tuple




```python
tup1[2]='hello'
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    ~\AppData\Local\Temp/ipykernel_5212/764570895.py in <module>
    ----> 1 tup1[2]='hello'
    

    TypeError: 'tuple' object does not support item assignment



```python
len(tup1)
```




    5




```python
tup2=(1,False,2.3,'hello',2+8j)
```


```python
tup2
```




    (1, False, 2.3, 'hello', (2+8j))




```python
tup1
```




    (1, True, 'OM', 2.34, (2+4j))




```python
tup1+tup2
```




    (1, True, 'OM', 2.34, (2+4j), 1, False, 2.3, 'hello', (2+8j))




```python
tup2+tup1
```




    (1, False, 2.3, 'hello', (2+8j), 1, True, 'OM', 2.34, (2+4j))




```python
tup1,tup2
```




    ((1, True, 'OM', 2.34, (2+4j)), (1, False, 2.3, 'hello', (2+8j)))




```python
tup3=(1,2,3)
```


```python
tup3*8
```




    (1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3)




```python
tup1*3+tup2*1
```




    (1,
     True,
     'OM',
     2.34,
     (2+4j),
     1,
     True,
     'OM',
     2.34,
     (2+4j),
     1,
     True,
     'OM',
     2.34,
     (2+4j),
     1,
     False,
     2.3,
     'hello',
     (2+8j))




```python
min(tup3)
```




    1




```python
max(tup3)
```




    3



# list in python


```python
l1=[1,'a',False]
```


```python
l1
```




    [1, 'a', False]




```python
type(l1)
```




    list




```python
a1=[1]
```


```python
type(a1)
```




    list




```python
l1[0]
```




    1




```python
l1[-1]
```




    False




```python
l1[0:3]
```




    [1, 'a', False]




```python
l1
```




    [1, 21, False]




```python
l2 = [1,'a',2,3,'OM']
```

l2


```python
l2
```




    [1, 'a', 2, 3, 'OM']




```python
l2[0]=100
```


```python
l2
```




    [100, 'a', 2, 3, 'OM']




```python
l2.pop()
```




    'OM'




```python
l2
```




    [100, 'a', 2, 3]




```python
l2.append('this is  strata')
```


```python
l2
```




    [100, 'a', 2, 3, 'this is  strata']




```python
l2.reverse()
```


```python
l2
```




    ['this is  strata', 3, 2, 'a', 100]




```python
l2.insert(2,2+4j)
```


```python
l2
```




    ['this is  strata', 3, (2+4j), 2, 'a', 100]




```python
l3=['mango','banna','apple','grapes']
l3
```




    ['mango', 'banna', 'apple', 'grapes']




```python
l3.sort()
```


```python
l3
```




    ['apple', 'banna', 'grapes', 'mango']




```python
l3*3+l2*5
```




    ['apple',
     'banna',
     'grapes',
     'mango',
     'apple',
     'banna',
     'grapes',
     'mango',
     'apple',
     'banna',
     'grapes',
     'mango',
     'this is  strata',
     3,
     (2+4j),
     2,
     'a',
     100,
     'this is  strata',
     3,
     (2+4j),
     2,
     'a',
     100,
     'this is  strata',
     3,
     (2+4j),
     2,
     'a',
     100,
     'this is  strata',
     3,
     (2+4j),
     2,
     'a',
     100,
     'this is  strata',
     3,
     (2+4j),
     2,
     'a',
     100]




```python
l1+l2+l3
```




    ['this is  strata',
     3,
     (2+4j),
     2,
     'a',
     100,
     'apple',
     'banna',
     'grapes',
     'mango']




```python
l1,l2,l3
```




    ([],
     ['this is  strata', 3, (2+4j), 2, 'a', 100],
     ['apple', 'banna', 'grapes', 'mango'])



# Dictionary


```python
d1={'applee':50,'mango':100,'banna':40}
```


```python
d1
```




    {'applee': 50, 'mango': 100, 'banna': 40}




```python
type(d1)
```




    dict




```python
d1.keys()
```




    dict_keys(['applee', 'mango', 'banna'])




```python
d1.values()
```




    dict_values([50, 100, 40])




```python
d1['grapes']=50
d1
```




    {'applee': 50, 'mango': 100, 'banna': 40, 'grapes': 50}




```python
d1['applee']=200
```


```python
d1
```




    {'applee': 200, 'mango': 100, 'banna': 40, 'grapes': 50, 'apple': 200}




```python
d2={'guava':80,'orange':70}
```


```python
d2
```




    {'guava': 80, 'orange': 70}




```python
d1.update(d2)
```


```python
d1
```




    {'applee': 200,
     'mango': 100,
     'banna': 40,
     'grapes': 50,
     'apple': 200,
     'guava': 80,
     'orange': 70}




```python
d2.update(d1)
```


```python
d2

```




    {'guava': 80,
     'orange': 70,
     'applee': 200,
     'mango': 100,
     'banna': 40,
     'grapes': 50,
     'apple': 200}




```python
d2.pop('banna')
```




    40




```python
d2
```




    {'guava': 80,
     'orange': 70,
     'applee': 200,
     'mango': 100,
     'grapes': 50,
     'apple': 200}



# If statement


```python
a=10
b=20
```


```python
if b>a:
    print('b is greateer then a')
```

    b is greateer then a
    


```python
if a>b:
    print('b is greater theb a')
```


```python
if a>b:
    print('a is greater then b')
else:
    print('b is greater then a')
```

    b is greater then a
    


```python
a=10
b=20
c=30
```


```python
if (a>c) & (a>b):
    print('a is the greatest')
elif (b>a) &(b>c):
    print('b is greatest')
else:
    print('c is greatest')
    
```

    c is greatest
    


```python
#if with tuple
```


```python
tup1=('a','b','c')
```


```python
if 'a' in tup1:
    print('value a is present in tup1')
```

    value a is present in tup1
    


```python
if 'd' in tup1:
    print('value d is present in tup1')
```


```python
#if with list
```


```python
l1=[1,2,3]
l1
```




    [1, 2, 3]




```python
if l1[2]==3:
    l1[2]=4
   
```


```python
l1
```




    [1, 2, 4]




```python
#if with dictionaary
```


```python
d1={'k1':20,'k2':40,'k3':50}
```


```python
d1
```




    {'k1': 20, 'k2': 40, 'k3': 50}




```python
if d1['k3']==50:
    d1['k3']=100
```


```python
d1
```




    {'k1': 20, 'k2': 40, 'k3': 100}



# looping statements

# While condition


```python
i=1
while i<=10:
        print(i)
        i=i+1
    
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    


```python
i=100
while i<=120:
    print(i)
    i=i+3
```

    100
    103
    106
    109
    112
    115
    118
    


```python
i=1
n=2
while i<=10:
    print(n ," * ",i," = ", n*i)
    i=i+1


```

    2  *  1  =  2
    2  *  2  =  4
    2  *  3  =  6
    2  *  4  =  8
    2  *  5  =  10
    2  *  6  =  12
    2  *  7  =  14
    2  *  8  =  16
    2  *  9  =  18
    2  *  10  =  20
    


```python
#while with list
```


```python
l1=[1,2,3,4]
```


```python
i=0
```


```python
while i<len(l1):
    l1[i]=l1[i]+100
    i=i+1
```


```python
l1
```




    [101, 102, 103, 104]



# For loop


```python
l1 = ['mango','graps','oranga','banana']
```


```python
for i in l1:
    print(i)
```

    mango
    graps
    oranga
    banana
    


```python
#multiple for loop
```


```python
l1=['book','laptop','chair','table']
l2=['black','orange','white']
```


```python
for i in l1:
    for j in l2:
        print(i,j)
```

    book black
    book orange
    book white
    laptop black
    laptop orange
    laptop white
    chair black
    chair orange
    chair white
    table black
    table orange
    table white
    

# Functions


```python
def hello():
    print('hello word')
```


```python
hello()
```

    hello word
    


```python
def add_10(x):
    return x+10
```


```python
add_10(16)
```




    26




```python
add_10(10)
```




    20




```python
def even_odd(x):
    if x%2==0:
        print(x, 'is even')
    else:
        print(x,'is oddd')
```


```python
even_odd(10)
```

    10 is even
    


```python
even_odd(5)
```

    5 is oddd
    


```python
g=lambda x: x*x*x
```


```python
g(7)
```




    343




```python
g(10)
```




    1000




```python
#lambda with filter
```


```python
l1 = [1,23,45,67,98,56]

final_list=list(filter(lambda x:(x%2!=0), l1))
```


```python
final_list
```




    [1, 23, 45, 67]




```python
#lambda with map
```


```python
l1 =[1,2,3,4,5,6,7,8]
```


```python
list_final=list(map(lambda x:x*2, l1))
```


```python
list_final
```




    [2, 4, 6, 8, 10, 12, 14, 16]




```python
from funktools import reduce
```


```python
l1=[1,2,3,4,5,6,7,8]
```


```python
sum=reduce(lambda x,y: x+y,l1)
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    ~\AppData\Local\Temp/ipykernel_3556/3401324226.py in <module>
    ----> 1 sum=reduce(lambda x,y: x+y,l1)
    

    NameError: name 'reduce' is not defined



```python
sum
```




    <function sum(iterable, /, start=0)>



# Python object Oriented Programming

# Classes


```python
#creating the first class 
```


```python
class Phone:
    def make_call(self):
        print('making call')
    def play_game(self):
        print('playing game')
```


```python
p1 = Phone()
```


```python
p1.make_call()
```

    making call
    


```python
p1.play_game()
```

    playing game
    


```python
#adding parameterss to the class 
```


```python
class Phone:
    def set_color(self,color):
        self.color=color
    def set_cost(self,cost):
        self.cost=cost
    def show_color(self):
        return self.color
    def show_cost(self):
        return self.cost
    def make_call(self):
        print('making call')
    def play_game(self):
        print('playing game')
```


```python
p2 = Phone()
```


```python
p2.set_color('black')
```


```python
p2.set_cost(10000)
```


```python
p2.show_color()
```




    'black'




```python
p2.show_cost()
```




    10000




```python
p2.make_call()
```

    making call
    


```python
p2.play_game()
```

    playing game
    

# creating class with constuctor


```python
class Employee:
    def __init__(self,name,age,salary,gender):
        self.name = name
        self.age = age
        self.salary = salary
        self.gender = gender
        
    def show_employee_details(self):
        print('name of employee is',self.name)
        print('age of employee is',self.age)
        print('salary of employee is',self.salary)
        print('gender of employee is',self.gender)
```


```python
e1 = Employee('Om',18,50000,'male')
```


```python
e1.show_employee_details()
```

    name of employee is Om
    age of employee is 18
    salary of employee is 50000
    gender of employee is male
    

# inheritance in python


```python
class vehicle:
    def __init__(self,mileage,cost):
        self.mileage = mileage
        self.cost = cost
        
    def show_vehicle_details(self):
        print('mileage of vihicle is',self.mileage)
        print('cost of vehicle is',self.cost)
```


```python
c1 = vehicle(50,5000000)
```


```python
c1.show_vehicle_details()
```

    mileage of vihicle is 50
    cost of vehicle is 5000000
    


```python
class car(vehicle):
    def show_car_details(seif):
        print('I am a car')
```


```python
c1 = car(200,1200000)
```


```python
c1.show_vehicle_details()
```

    mileage of vihicle is 200
    cost of vehicle is 1200000
    


```python
c1.show_car_details()
```

    I am a car
    

# over_riding the init method


```python
class car(vehicle):
    def __init__(self,mileage,cost,tyers,hp):
        self.mileage = mileage
        self.cost = cost
        self.tyers = tyers
        self.hp = hp
        
    def show_car_details(self):
        print('tyers of vihicle is',self.tyers)
        print('hp of vehicle is',self.hp)
        print('i am a car')
```


```python
c1 = car(300,2000000,4,400)
```


```python
c1.show_car_details()
```

    tyers of vihicle is 4
    hp of vehicle is 400
    i am a car
    

# multiple inheritance


```python
class perent1:
    def assign_string_one(self,str1):
        self.ster1 = str1
    def assign_string_one(self):
        return self.str1

```


```python
class perent2:
    def assign_string_two(self,str2):
        self.str2 = str2
    def assign_string_two(self):
        return self.str2
```


```python
class child(perent1,perent2):
    def assign_string_three(self,str3):
        self.str3 = str3
    def assign_string_three(self):
        self.str3
```


```python
my_child = child()

#some work is due
```

# multi-level inheritanc


```python
class parent:
    def get_name(self,name):
        self.name = name
    def show_name(self):
        return self.name
```


```python
class child(parent):
    def get_age(self,age):
        self.age = age
    def show_age(self):
        return self.age
```


```python
class grandchild(child):
    def get_gender(self,gender):
        self.gender = gender
    def get_gender(self):
        return self.gender
    
```


```python
gc = grandchild()
```


```python
gc.get_name('om')
```


```python
gc.get_age(18)
```


```python
gc.show_name()
```




    'om'




```python
gc.show_age()
```




    18



# Thanks for Watching

# Best Regards


# Om Prakash
