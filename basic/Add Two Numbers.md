## 🧮 Problem 3: Add Two Numbers

**Problem Statement:**  
Your task is very simple: given two integers A and B, write a program to add these two numbers and output the sum.

🔗 Problem Link: (https://www.codechef.com/problems/FLOW001)

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

        cout << x + y << endl;
    }

    return 0;
}
