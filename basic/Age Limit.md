## 🧮 Problem 4: Practice problem - Age Limit

**Problem Statement:**  
Chef wants to appear in a competitive exam. To take the exam, there are following requirements: Minimum age limit is X (i.e. Age should be greater than or equal to X). Age should be strictly less than Y. Chef's current Age is A. Find whether he is currently eligible to take the exam or not.

🔗 Problem Link: ([https://www.codechef.com/problems/FLOW001](https://www.codechef.com/learn/course/cpp-beginner/BC00BC09/problems/CSC02A)

solution: 


```cpp
// Solution as follows

#include <iostream>
#include <string>
using namespace std;

int main() 
{
 int t;
 cin>>t;
 while(t--)
  { 
   int X,Y,A;
   
   cin>>X>>Y>>A;       
   if (A >= X && A < Y)
   {
  
   cout<<"YES"<<endl;        
   }
   else
   {
    cout<<"NO"<<endl;
   }
  }
 return 0;
}
