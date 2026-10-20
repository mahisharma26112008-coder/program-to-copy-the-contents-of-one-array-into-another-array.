# program-to-copy-the-contents-of-one-array-into-another-array.

#include<iostream>
  using namespace std;
    int main(){
        int n;
        cout<<"enter the size of array ";
        cin>>n;
        
        int arr1[n],arr2[n];
        
        for(int i=0;i<n;i++){
        cout<<"enter the elements of array"<<i+1<<"\n";
        cin>>arr1[i];
    }
    
    for(int i=0;i<n;i++){
        arr2[i]=arr1[i];
    }
    
    cout<<"elements of first array  :"<<"\n";
    for(int i=0;i<n;i++){
        cout<<arr1[i]<<"\n";
    }
    
    cout<<"elements of second array  :"<<"\n";
    for(int i=0;i<n;i++){
        cout<<arr2[i]<<"\n";
    }
    
    
    return 0;
    }
        
