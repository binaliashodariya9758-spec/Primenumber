#include<iostream>
using namespace std;

int main()
{
    int n,i=2,t,cnt=0;
    
    cout<<"Enter n:";
    cin>>n;
    
    t=n;
    
    while(i<n)
    {
        t=n%i;
        
        if(t==0)
        {
            cnt++;
        }
        i++;
    }
    
    if(cnt==0)
    {
        cout<<"This is prime number"<<endl;
    }
    else
    {
        cout<<"This is not prime number"<<endl;
    }
    
    return 0; 
    
}
