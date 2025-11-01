## 🧮 Problem 14: Kitchen Timings

**Problem Statement:**  
The working hours of Chef’s kitchen are from X pm to Y pm (1≤X<Y≤12). Find the number of hours Chef works.

🔗 Problem Link: https://www.codechef.com/problems/KITCHENTIME

solution: 


```cpp

#include<bits/stdc++.h>
using namespace std;

int main(){
    int t;
    cin >> t;

    while(t--){
        int x, y;
        cin >> x >> y;

        cout << (y - x) << endl;
    }

    return 0;
}
