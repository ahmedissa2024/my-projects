>>> 2+6
8
>>> 3-4*2
-5
>>> (30-5*3)/4
3.75
>>> 8/2
4.0
>>> 17//3
5
>>> 17/3
5.666666666666667
>>> 17%3
2
>>> 5*3+2
17
>>> 5**2
25
>>> 2**7
128

>>> 4 * 3.75 - 1
14.0
>>> tax = 12.5 / 100
>>> price = 100.50
>>> price * tax
12.5625
>>> price + _
113.0625
>>> round(_, 2)
113.06

>>> 'spam eggs' 
'spam eggs'
>>>"Paris rabbit got your back :)! Yay!"  
'Paris rabbit got your back :)! Yay!'
>>> '1975'  
'1975'

>>> 'doesn\'t' 
"doesn't"
>>> "doesn't"  
"doesn't"
>>> '"Yes," they said.'
'"Yes," they said.'
>>> "\"Yes,\" they said."
'"Yes," they said.'
>>> '"Isn\'t," they said.'
'"Isn\'t," they said.'

>>> s = 'First line.\nSecond line.'  
>>> s 
'First line.\nSecond line.'
>>> print(s)  
First line.
Second line.

>>> print('C:\some\name')  
C:\some
ame
>>> print(r'C:\some\name')  
C:\some\name

>>>print("""\
Usage: thingy [OPTIONS]
     -h                        Display this usage message
     -H hostname               Hostname to connect to
""")

Usage: thingy [OPTIONS]
     -h                        Display this usage message
     -H hostname               Hostname to connect to
>>> 3 * 'un' + 'ium'
'unununium'

>>> 'Py' 'thon'
'Python'

>>> text = ('Put several strings within parentheses '
        'to have them joined together.')
>>> text
'Put several strings within parentheses to have them joined together.'
>>>
>>> prefix = 'Py'
>>> prefix 'thon'  # can't concatenate a variable and a string literal
  File "<stdin>", line 1
    prefix 'thon'
           ^^^^^^
SyntaxError: invalid syntax
>>> ('un' * 3) 'ium'
  File "<stdin>", line 1
    ('un' * 3) 'ium'
               ^^^^^
SyntaxError: invalid syntax
>>> word = 'Python'
>>> word[0] 
'P'
>>> word[5]  
'n'
>>> word[-1]  
'n'
>>> word[-2]  
'o'
>>> word[-6]
'P'
>>> word[0:2] 
'Py'
>>> word[2:5]  
'tho'
>>> word[:2]  
'Py'
>>> word[4:]   
'on'
>>> word[-2:] 
'on'
>>> word[:2] + word[2:]
'Python'
>>> word[:4] + word[4:]
'Python'






>>> squares = [1, 4, 9, 16, 25]
>>> squares
[1, 4, 9, 16, 25]

>>> squares[0] 
1
>>> squares[-1]
25
>>> squares[-3:]  
[9, 16, 25]
>>>
>>> squares + [36, 49, 64, 81, 100]
[1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

>>> cubes = [1, 8, 27, 65, 125] 
>>> 4 ** 3  
64
>>> cubes[3] = 64  
>>> cubes
[1, 8, 27, 64, 125]

>>> cubes.append(216) 
>>> cubes.append(7 ** 3)  
>>> cubes
[1, 8, 27, 64, 125, 216, 343]

>>> rgb = ["Red", "Green", "Blue"]
>>> rgba = rgb
>>> id(rgb) == id(rgba)  # they reference the same object
True
>>> rgba.append("Alph")
>>> rgb
["Red", "Green", "Blue", "Alph"]
>>>
>>> correct_rgba = rgba[:]
>>> correct_rgba[-1] = "Alpha"
>>> correct_rgba
["Red", "Green", "Blue", "Alpha"]
>>> rgba
["Red", "Green", "Blue", "Alph"]
>>>
>>> letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g']
>>> letters
['a', 'b', 'c', 'd', 'e', 'f', 'g']
>>> letters[2:5] = ['C', 'D', 'E']
>>> letters
['a', 'b', 'C', 'D', 'E', 'f', 'g']
>>> letters[2:5] = []
>>> letters
['a', 'b', 'f', 'g']
>>> letters[:] = []
>>> letters
[]

>>> letters = ['a', 'b', 'c', 'd']
>>> len(letters)
4

>>> a = ['a', 'b', 'c']
>>> n = [1, 2, 3]
>>> x = [a, n]
>>> x
[['a', 'b', 'c'], [1, 2, 3]]
>>> x[0]
['a', 'b', 'c']
>>> x[0][1]
'b'

>>> a, b = 0, 1
>>> while a < 10:
 ...   print(a)
 ...   a, b = b, a+b
0
1
1
2
3
5
8

>>> i = 256*256
>>> print('The value of i is', i)
The value of i is 65536
>>>
>>> a, b = 0, 1
>>> while a < 1000:
...    print(a, end=',')
...    a, b = b, a+b
...
0,1,1,2,3,5,8,13,21,34,55,89,144,233,377,610,987,
