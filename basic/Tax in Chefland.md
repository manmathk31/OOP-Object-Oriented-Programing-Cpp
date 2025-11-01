## 🧮 Problem 13: Tax in Chefland

**Problem Statement:**  
DAIICT college students want to attend an IPL match.  A total of N students from the college want to go while only M tickets are available for the match. Determine how many students won't be able to book tickets.

🔗 Problem Link:https://www.codechef.com/problems/TAXES

solution: 


```cpp

#include <bits/stdc++.h>
using namespace std;

int main() {
    int t;
    cin >> t;

    while(t--){
        int x;
        cin >> x;
            
        if(x > 100)    
            cout << x - 10 << endl;
        else            
            cout << x << endl;
    }

    return 0;
}
