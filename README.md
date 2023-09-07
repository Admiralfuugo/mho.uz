# mho.uz
Rasmiy saytga xush kelibsiz


  About me:  https://admiralfuugo.github.io/about-me/ <br>
  Instagram:https://www.instagram.com/fuugo13 <br>
  Telegram:https://t.me/gooyu13 <br>
  Facebook:https://facebook.com/akbaralianvarov13  <br>
  Owner: https://aktahiuzz.netlify.app <br>
  Git-Hub: https://github.com/Admiralfuugo <br>






  
------------------------------------------------------------------------------------------
toq son
#include <iostream>

using namespace std;

int main()
{
 
long long x,y;
cin>>x;
int k=0;
while(x>0)
{
    y=x%10; k+=1;
    if(y%2==0)
    {
        cout<<"No";
        return 0;
        
    }
    x/=10;
}
if(k%2==1)
cout<<"YES";
else
cout<<"NO";
}

-------------------------------------------------------------------------------------------------
qiziqarli
a = int(input())
print("Qiziqarli")

------------------------------------------------------------------------------------------------
a+b
print(sum(map(int,input().split())))

-------------------------------------------------------------------------------------------------
massivni uchirish
#include <iostream>
#include <cmath>
#include <string>
using namespace std;
int main()

{
int n,a[101]={0},k,max=0,sum=0;
cin>>n;
for(int i=0;i<n;i++)
{
    cin>>k;
    a[k]++;
}
for(int i=0;i<101;i++)
{
    if(a[i]>a[max])
    max=i;
}
cout<<n-a[max];
}

-------------------------------------------------------------------------------------


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

---------------------------------------------
