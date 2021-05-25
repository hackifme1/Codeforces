// By Chandramani Kumar
// Keep moving and must be simple bro!!!!!
// Espérons le meilleur mais préparez-vous au pire 😎


Cpp code :

#include <bits/stdc++.h>
using namespace std;

typedef long long ll;

int main() {
	ll t;
	cin>>t;
	while(t--)
	{
		ll n,i,j,k;
		cin>>n;
		char s[n];
		for(i=0;i<n;i++)
		cin>>s[i];
		
		if(n==4)
		{
			if(s[0]=='2'&&s[1]=='0'&&s[2]=='2'&&s[3]=='0')
			cout<<"YES"<<endl;
			else
			cout<<"NO"<<endl;
		}
		else
		{
			if(s[0]=='2'&&s[n-1]=='0'&&s[n-2]=='2'&&s[n-3]=='0')
			cout<<"YES"<<endl;
			else if(s[0]=='2'&&s[1]=='0'&&s[n-1]=='0'&&s[n-2]=='2')
			cout<<"YES"<<endl;
			else if(s[0]=='2'&&s[1]=='0'&&s[2]=='2'&&s[n-1]=='0')
			cout<<"YES"<<endl;
			else if(s[0]=='2'&&s[1]=='0'&&s[2]=='2'&&s[3]=='0')
			cout<<"YES"<<endl;
			else if(s[n-4]=='2'&&s[n-1]=='0'&&s[n-2]=='2'&&s[n-3]=='0')
			cout<<"YES"<<endl;
			else
			cout<<"NO"<<endl;
		}
		
	}
	return 0;
}
