# avg-of-even-no
#average of even no using range
n=int(input())
a=list(map(int,input().split()))
e=[]
for i in range(n):
  if a[i]%2==0:
    e.append(a[i])
print(sum(e)//len(e)) 


#average of even no without using range
n=int(input())
a=list(map(int,input().split()))
e=[]
for i in a:
  if i%2==0:
    e.append(i)
print(sum(e)//len(e)) 

