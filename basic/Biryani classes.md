## 🧮 Problem 10: Biryani classes


**Problem Statement:**  
According to a recent survey, Biryani is the most ordered food. Chef wants to learn how to make world-class Biryani from a MasterChef. Chef will be required to attend the MasterChef's classes for X weeks, and the cost of classes per week is Y coins. What is the total amount of money that Chef will have to pay?

🔗 Problem Link: https://www.codechef.com/problems/BIRYANI

solution: 


```cpp

#include <bits/stdc++.h>
using namespace std;

int main() {
    int t;
    cin >> t;

    while(t--){
        int x, y;
        cin >> x >> y;
          
        cout << x * y << endl;
    }

    return 0;
}
