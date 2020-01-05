# V7xStyle
#### There are 3 classes that you can work on
* [Animation](https://github.com/No-Name-404/V7xStyle/blob/master/README.md#animation-class)
* [Style](https://github.com/No-Name-404/V7xStyle/blob/master/README.md#style-class) 
* Text

Also, you can control the colors easily
* Colors


# The method of work
## Animation class
###  SlowLine function
```
from V7xStyle import Animation
text = '''
text text text text text text
text text text text text text
text text text text text text
text text text text text text
text text text text text text
text text text text text text
'''
Animation.SlowLine(text, time=0.001)
```
Only 2 values in this function
__________________________
###  SlowText function
```
from V7xStyle import Animation
text = 'text text text text text text'

Animation.SlowText(text, end=False)
```
Only 2 values in this function
__________________________
###  Loading function

example 1... 
```
from V7xStyle import Animation

Animation.Loading( text=' text ' )
```
example 2...
```
from V7xStyle import Animation

AQ = [ str(i+1) for i in range(100) ]
Animation.Loading(text=' Hi %',
                  Animation=AQ,
                  repeat=1)
```
example 3...
```
from V7xStyle import Animation

AQ = ['a','b','c']
Animation.Loading( text=' text - ',
                   Animation=AQ,
                   repeat=10,
                   time=0.5 )
```
Only 4 values in this function
__________________________
###  Text function
```
from V7xStyle import Animation
from V7xStyle import (R,G,W,B,P,C,Bl,Y)

Animation.Text( UpperTextColor=R,
                LowerTextColor=W,
                Animation='text.text...',
                text=' My text- ',
                time=0.2,
                repeat=2 )
```
Only 6 values in this function
__________________________
###  Downloading function

example 1
```
from V7xStyle import Animation

Animation.Downloading()
```
example 2
```
from V7xStyle import Animation

AQ = ['|','█','▒','|']
CQ = [W,G,W,W]
Animation.Downloading( Animation=AQ,
                       Colors=CQ,
                       text='Loading',
                       time=0.2,
                       width=25 )
```
Only 5 values in this function

___
## Style class
### Center function
```
from V7xStyle import Style

a = '12345'
b = '123'
c = '1'

S = Style( a,b,c ).Center
print (S)
```
No values in this function
___
###  Square function
example 1
```
from V7xStyle import Style

S = Style('text').Square()
print(S)
```
example 2
```
from V7xStyle import Style

S = Style('A','B','C').Square()
print(S)

SQ = ['text']*10
S = Style(*SQ).Square()
print(S)
```
