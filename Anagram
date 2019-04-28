#include<bits/stdc++.h>
using namespace std;
int count(string s1,int n1,string s2,int n2)
{
    int arr1[26]={0};
    int arr2[26]={0};
    int i,count=0;
    for(i=0;i<n1;i++)
    arr1[s1[i]-'a']++;
    for(i=0;i<n2;i++)
    arr2[s2[i]-'a']++;
    for(i=0;i<26;i++)
    count=count + (min(arr1[i],arr2[i]));
    return count;
}

int main()
{
    int i,t,n1,n2;
	string s1;
	string s2;
	cin>>t;
	for(i=0;i<t;i++)
	{
	    cin>>s1>>s2;
	    n1=s1.size();
	    n2=s2.size();
	    cout<<n1+n2-(2*count(s1,n1,s2,n2))<<endl;

	}

	return 0;
}
