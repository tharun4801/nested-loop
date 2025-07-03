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
