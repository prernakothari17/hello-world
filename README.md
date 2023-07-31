#include <iostream>
#include<bits/stdc++.h>
using namespace std;

bool solve(int arr[],int target){
    int n=arr,size();
    sort(arr,arr+n);
    int i=0,j=n-1;
    while(i<j){
        intsum=arr[i]+arr[j];
        if(sum==target){
            return 1;
        }
        else if(sum>target){
            j--;
        }
        else{
            i++;
        }
    
}
return 0;
int main()
{
   int arr[5]={1,7,9,55,44}
   int target=10;
   if(solve(arr,target)){
       cout<<"It exists"<<endl;
   }
   else
   {
       cout<<"It doesn't exist"<<endl;
   }

    return 0;
}
