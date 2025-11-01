## 🧮 Problem 6: How many unattempted problems

**Problem Statement:**  
CodeChef recently revamped its practice page to make it easier for users to identify the next problems they should solve by introducing some new features:   1. Recent Contest Problems - contains only problems from the last 2 contests,      2. Separate Un-Attempted, Attempted, and All tabs,                                                            3. Problem Difficulty Rating - the Recommended dropdown menu has various difficulty ranges so that you can attempt the problems most suited to your experience,                                                                                                                                            4. Popular Topics and Tags.  Our Chef is currently practicing on CodeChef and is a beginner. The count of ‘All Problems’ in the Beginner section is X. Our Chef has already ‘Attempted’ Y problems among them. How many problems are yet ‘Un-attempted’?

🔗 Problem Link: https://www.codechef.com/problems/PRACLIST

solution: 


```cpp
#include <bits/stdc++.h>

using namespace std;

int main() {
    int x, y;
    cin >> x >> y;
            
    cout << abs(x - y) << endl;

    return 0;
}
