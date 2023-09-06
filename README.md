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



def minimum_additional_chars(password):
    min_length = 6
    min_digit = 1
    min_lower = 1
    min_upper = 1
    min_special = 1
    special_chars = "!@#$%^&*()-+"

    additional_chars = 0

    # Check length
    if len(password) < min_length:
        additional_chars += min_length - len(password)

    # Check for at least one digit
    if not any(char.isdigit() for char in password):
        additional_chars += min_digit

    # Check for at least one lowercase letter
    if not any(char.islower() for char in password):
        additional_chars += min_lower

    # Check for at least one uppercase letter
    if not any(char.isupper() for char in password):
        additional_chars += min_upper

    # Check for at least one special character
    if not any(char in special_chars for char in password):
        additional_chars += min_special

    return additional_chars

# Kiruvchi ma'lumotlarni olish
n = int(input())
password = input()

# Parol uchun kerakli qo'shimcha belgilar sonini hisoblash
additional_chars = minimum_additional_chars(password)

# Natijani chiqarish
print(additional_chars)
