# write-a-program-to-print-sum-of-n-fibonacci-series
a=-1
b=1
n=int(input())
for i in range(1,n+1):
c=a+b
print(c)
a=b
b=c
