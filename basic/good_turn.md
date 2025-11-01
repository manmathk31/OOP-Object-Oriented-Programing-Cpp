## 🧮 Problem 1: Chef and Chefina — Good Turn

**Problem Statement:**  
Chef and Chefina are playing with dice. In one turn, both of them roll their dice at once.  
A turn is considered **good** if the sum of the numbers on their dice is greater than 6.  

Given that in a particular turn Chef and Chefina got **X** and **Y** on their respective dice,  
determine whether the turn was good.

🔗 **Problem Link:** [GDTURN - CodeChef](https://www.codechef.com/problems/GDTURN)

solution: 

#include <iostream>
using namespace std;

int main() {
    int t, x, y;
    cin >> t;
    while (t--) {
        cin >> x >> y;
        if (x + y > 6)
            cout << "YES\n";
        else
            cout << "NO\n";
    }
    return 0;
}
