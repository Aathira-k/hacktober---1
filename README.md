# hacktober---1
#include <iostream>
#include<cstdio>
using namespace std;
int main()
{
	char a[10];
	char*p;
	int c=0;
	cout<<"enter the string";
	gets(a);
	p=a;
	while(*p!="/0")
	{
		if(*p=="a"||*p=="e"||*p=="i"||*p=="o"||*p=="u"||*p=="A"||*p="E"||*p=="U"||*p=="I"||*p="O")
		{
			c=c+1;
		}
		p=p+1;
	}
			
	}		
	return 0;
}	
