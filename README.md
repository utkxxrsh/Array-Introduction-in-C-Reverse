# Array-Introduction-in-C-Reverse
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    int arr[10000];
    int n;
    cin>>n;
    int z;
    for(int i=0;i<n;i++){
        cin>>arr[i];

    }  
    for(int j=n-1;j>=0;j--){
        cout<<arr[j]<<" ";
    }
    return 0;
}
