# 10.count-prime-num-in-a-given-range-
a= int(input())
b= int(input())
s=0
for n in range(a,b):
    f=0
    for i in range(1,n+1):
        if n%i==0:
            f=f+1
    if f==2:
        s=s+1
print(s)
