# mho.uz
Rasmiy saytga xush kelibsiz


  About me:  https://admiralfuugo.github.io/about-me/ <br>
  Instagram:https://www.instagram.com/fuugo13 <br>
  Telegram:https://t.me/gooyu13 <br>
  Facebook:https://facebook.com/akbaralianvarov13  <br>
  Owner: https://aktahiuzz.netlify.app <br>
  Git-Hub: https://github.com/Admiralfuugo <br>






  


------------------------------------------------------------------





============================================================








-------------------------------------------------------------------------------------------------
**oson hisobla**

n, k = map(int, input().split())
s, p = 0, 1
while n>0:
    d = n%k
    s += d
    p *= d
    n //= k
print(p-s)
=======================================================*

**massivni uchirish**

#include <iostream>
#include <cmath>
#include <string>
using namespace std;
int main()

{
int katta=0,yig=0;
int son,x[101]={0},b;katta=0,yig=0;


cin>>son;
for(int i=0;i<son;i++)
{
cin>>b;
x[b]++;
}
for(int i=0;i<101;i++)
{
if(x[i]>x[katta])
katta=i;
}
cout<<son-x[katta];
}

-------------------------------------------------------------------------------------
**parol**

def qosh(kod):
    count = 0
    if any(i.isdigit() for i in kod) == False:
        count += 1
    if any(i.islower() for i in kod) == False:
        count += 1
    if any(i.isupper() for i in kod) == False:
        count += 1
    if any(i in '!@#$%^&*()-+' for i in kod) == False:
        count += 1
    return max(count, 6 - len(kod))

n = int(input().strip())
kod = input().strip()
print(qosh(kod))

---------------------------------------------_________
**O'qlar**

a=input();s=0;m=0
for i in range(len(a)):
 if len(a)<5:
 break
 elif i<len(a)-4:
 if a[i]=='>' and a[i+1]=='>' and a[i+2]=='-' and
a[i+3]=='-' and a[i+4]=='>':
 s=s+1
 elif a[i]=='<' and a[i+1]=='-' and a[i+2]=='-' and
a[i+3]=='<' and a[i+4]=='<':
 m=m+1
d=s+m
print(int(d))

_________________________________________________________________________

**teatr**
from math import ceil
 
n, m, a = map(int, input().split())
print(ceil(n/a)*ceil(m/a))
______________________________________________________________________


