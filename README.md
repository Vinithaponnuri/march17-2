PROGRAMME:
s=input()
l=list(s)
lo=0
u=0
d=0
s=0
for i in l:
    if (i.islower()):
        lo=lo+1
    elif (i.isupper()):
        u=u+1
    elif (i.isdigit()):
        d=d+1
    else:
       s=s+1
if (lo>0 and u>0 and d>0 and s>0):
    print('valid password')
else:
    print('invalid password')
        
OUTPUT:
VinnU$123
valid password
