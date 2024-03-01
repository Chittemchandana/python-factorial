# python-factorial
# approach1 factorial even&odd addition
s,e =map(int,input().split())
s=0
for i in range(s,e+1):
  r=1
  for j in range(1,i+1):
    r=r*j
  s=s+r
print(s)

# approach2
s,e =map(int,input().split())
a=[]
for i in range(s,e+1):
  r=1
  for j in range(1,i+1):
    r=r*j
  a.append(r)
print(sum(a))

# approach3 even numbers factorial
s1=0
s,e=map(int,input().split())
for i in range(s,e+1):
  if(i%2==0):
    r=1
    for j in range(1,i+1):
      r=r*j
    s1=s1+r
print(s1) 
# approach4
n=int(input())
a=list(map(int,input().split()))
x=[]
for i in range(n):
  if a[i] not in x:
    x.append(a[i])
print(x)
