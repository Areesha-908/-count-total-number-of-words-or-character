#  count total number of words or character
#include<iostream>
#include<conio.h>
using namespace std;
int main()
{
int countch=0,countwd=1;
char ch='a';
cout<<"enter a phrase"<<endl;
while(ch!='\r')
{
ch=getche();
if(ch==' ')
countwd++;
else
countch++;
}
cout<<endl<<"Words="<<countwd<<endl;
cout<<"character="<<countch-1;
return 0;
}

 
