## 🧮 Problem 12: Determine the Score

**Problem Statement:**  
Chef appeared for a placement test. There is a problem worth X points. Chef finds out that the problem has exactly 10 test cases. It is known that each test case is worth the same number of points. Chef passes N test cases among them. Determine the score Chef will get.

🔗 Problem Link: https://www.codechef.com/problems/DETSCORE

solution: 


```cpp

#include<bits/stdc++.h>
using namespace std;

int main(){
    int t;
    cin >> t;

    while(t--){
        int x, n;
        cin >> x >> n;

        cout << n * (x / 10) << endl;
    }

    return 0;
}
