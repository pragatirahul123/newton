```ngMeta
name: Dry Run of Variables
completionMethod: manual
```

## Humein inn programs ka dry run karna hai:
### Kaise Use Karein
Aap sab ko yeh questions pen and paper use kar kar karne hai. Saari exercises aap apni notebooks mei solve kar kar, ek doosre ke solution ko check karayein.

Jab aap ko confidence ho ki aap ka solution theek hai, tab aap kisi senior se solution verify kara kar aage badh sakte hai.

Yeh bahut important hai ki yeh course aap bahut dhyaan se karein, kyuki programming ke basics iss course mei develop ho jayenge.

<!-- TODO : Dry run kaise karte hai iske liye yeh video dekho. -->
1.
```python
a = 1
b = 2
b = a
```
2.
```python
 a = 1
 b = 2
 c = b
 b = a 
 a = c
```
3.
```python
a = 1
b = a*2
c = b*2
a = c*2
```
4.
```python
 a = 100
 a = a + 50
 a = a / 3
 a = a * 2
```
5.
```python
 a = 10
 b = 10
 c = a * b
 a = c - b
 b = c + a
 c = a * c
```
6.
```python
seconds = 30

days = seconds/60*60*24
seconds = seconds%(60*60*24)

hours = seconds/60*60
seconds =seconds/(60*60)

minute = seconds/60
seconds = seconds/60

print days, hours, minute, seconds
```
7.
```python
amount = 8712
note2000 = amount/2000
amount = amount%2000

note500 = amount/500
amount = amount%500

note100= amount/100
amount = amount/100

note50 = amount/50
amount = amount%50

note10 = amount/10
amount = amount/10

note5 = amount/5
amount = amount%5

note2 = amount/2
amount = amount%2

note1 = amount/1
amount = amount%1

print note2000, note500, note100, note50, note10, note5, note2, note1
```
8.
```python
seconds = 3760

days = seconds/(60*60*24)
seconds = seconds%(60*60*24)

minute = seconds%60

hours = minutes/60

print days, hours, minute, seconds
```