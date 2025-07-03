#armstrong number
n=eval(input("enter the number:"))
t=n
s=0
l=len(str(n))
while n!=0:
    d=n%10
    s+=d**l
    n=n//10
if t==s:
    print("armstrong number",t)
else:
    print("not an armstrong number",t)
OUTPUT:
enter the number:999
not an armstrong number 999
enter the number:153
armstrong number 153

#nivens number
n=eval(input("enter the number:"))
t=n
s=0
while t>0:
    s+=t%10
    t//=10
if n%s==0:
    print("nivens number",n)
else:
    print("not a nives number",n)
OUTPUT:
enter the number:156
nivens number 156
enter the number:123
not a nives number 123

#TABLES FORMAT
n=eval(input("enter the number:"))
for i in range(1,11):
    print(str(n)+"*" + str(i) + "=" + str(i*n))
OUTPUT:
enter the number:11
11*1=11
11*2=22
11*3=33
11*4=44
11*5=55
11*6=66
11*7=77
11*8=88
11*9=99
11*10=110
enter the number:256
256*1=256
256*2=512
256*3=768
256*4=1024
256*5=1280
256*6=1536
256*7=1792
256*8=2048
256*9=2304
256*10=2560

