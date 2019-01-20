#include<bits/stdc++.h>
using namespace std;
int main()
{
	int n,b;
	int a=0;
	scanf("%d",&n);
	      for(int i=0;i<n;i++)
	      {
		     scanf("%d",&b);
		     a=a^b;
	      }
	      printf("%d",a);
    return 0;
}
