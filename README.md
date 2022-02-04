# 04.02-2022-lab
1
strA = "Abrakadabra"
print(strA[2])
print(strA[len(strA)-2])
print(strA[:5])
print(strA[:-2])
print(strA[::2])
print(strA[1::2])
print(strA[::-1])
print(strA[::-2])
print(len(str))

2
print(input()
count(' ') + 1)

3
stroka = input()
print(stroka[(len(stroka) + 1) // 2:] + stroka[:(len(stroka) + 1) // 2])

4
stroka = input()
w1 = stroka[:stroka.find(' ')] 
w2 = stroka[stroka.find(' ') + 1:] 
print(w2 + ' ' + w1)

5
s = input()
a = s.find('f')
b = s.rfind('f') 
if a == -1: 
     print() 
elif a == b: 
      print(a) 
else: 
    print(a, b)
    
6
a = input()
num = 0
for i in range(len(a)):
    if a[i] == "f":
        num += 1
        if num == 2:
            print(i)

if num == 1:
    print('-1')
elif "f" not in a:
    print('-2')
    
7
x = input()
y = x[0:x.find('h')] + x[x.rfind('h')+1:]
print(y)
    
8
str = input()
print(str.replace('1', 'one'))

9
x = input()
y = x[x.find('h')+1:x.rfind('h')]
print(y*2)

10
print(input().replace('1', 'one'))

11
x = input()
y = []
y.extend(x)
while '@' in y:
	y.remove('@')
print(*y, sep='')	

12




