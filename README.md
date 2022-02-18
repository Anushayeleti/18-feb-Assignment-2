n=int(input('enter number:'))
f=1 
sum=0
for i in range(1,n+1):
    f=f*i 
    sum=sum+f
print('factorial of a given no is:',f)
print('  sum of factorials:',sum)

output:enter number:5
       factorial of a given no is:120
        sum of factorials:153
