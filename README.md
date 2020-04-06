# My_Style 1.1

- Animation
- Style
- Text
- Color
___
### How to use ?
#### Animation {
```python3
#----------------------------------------#
#                                        #
#        ''' Class Animation '''         #
from My_Style import Animation
A = Animation
text ='''
text texttext text texttext
text texttext text texttext
text texttext text texttext
text texttext text texttext
text texttext text texttext
'''
# Class Animation (Functions)
A.SlowText(text)
A.SlowLine(text,t=0.1) # t = time
A.SlowIndex(text,t=0.01) # t = time
A.Text()
A.Loading()
A.DL()
''' args Text(CUT=Color,
              CLT=Color,
              t=Integer or float,
              text=string,
              AT=list,
              repeat=Integer)'''

''' args Loading(t=Integer or float,
                 text=string,
                 AT=list,
                 repeat=Integer)'''

''' args Loading(t=Integer or float,
                 text=string,
                 AT=list,
                 width=Integer)'''
#                                        #
#----------------------------------------#
#                                        #
```
#### }
#### Style {
```python3
#----------------------------------------#
#                                        #
#           ''' Class Style '''          #
from My_Style import Style
S = Style
# Class Style (Functions)
Square = S('A','B','C').Square()
Center = S('123','1','12345').Center()

# Output...
print(Square)
print(Center)

''' args Square(
                Color=Color,
                padding_x=Integer,
                padding_y=Integer,
                space=Integer,
                cols=Integer,
                Square=Integer,
                Equal=boolean) '''
#                                        #
#----------------------------------------#
#                                        #
```
#### }
#### Text {
```python3
#----------------------------------------#
#                                        #
#           ''' Class Text '''           #
from My_Style import Text
T = Text
# Class Text (Functions)
Figlet = T('text').Figlet()
Toilet = T('text').Toilet()
GS = T('text').GS()
DS = T(True).DS('\n\ntext\n\n')
CTL = T('text').CTL(top=2,right=2,down=2)

# Output...
print(Figlet)
print(Toilet)
print(GS)
print(DS)
print(CTL)
#                                        #
#----------------------------------------#
#                                        #
```  
#### }

#### Color {
```python3
#----------------------------------------#
#                                        #
#           ''' Class Color '''          #
from My_Style import Color

Color.Theme('light')
text_light = Color.reader('W#tG#eC#xB#t')

Color.Theme('dark')
text_dark = Color.reader('W#tG#eC#xB#t')

Color.add(
'\033[1;95m',
'\033[1;96m',
'\033[1;97m',
) # if you use new colors,they should be placed here

print (text_light)
print (text_dark)
#                                        #
#----------------------------------------#
#                                        #
```  
#### }
