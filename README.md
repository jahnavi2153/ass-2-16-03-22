# ass-2-16-03-22
#write a program to separate even and odd numbers from the digit.
n=[]
even=[]
odd=[]
number=int(input(''))
for i in range(1,number+1):
    a=int(input())
    n.append(a)
for j in range(number):
    if(n[j]%2==0):
        even.append(n[j])
    else:
        odd.append(n[j])

print('even:',even)
print('odd:',odd)

ouput:
5
87
21
46
89
32
even:[46,32]
odd:[87,21,89]
