include <iostream>
#include <bits/stdc++.h>
using namespace std;

int main()
{

    int t, i;
    cout<<"Enter How many test cases :"<<endl;;
    cin>>t;

    while(t--)  
    {
        int n;

        cin>>n;

        long long int arr[n];  // craete array with size namespace

        long long int prefix[n]={0};  // take prefix array with size namespace

        for(i=1;i<=n;i++)
        {
            cin>>arr[i];        
            prefix[i]=prefix[i-1]+arr[i];
        }

        int Q;

        cin>>Q;

        while(Q--)
        {
            int L, R;

            cin>>L>>R;

            cout<<prefix[R]-prefix[L-1];

        }



    }


    return 0;
}
