## 🧮 Problem 5: Saving Taxes

**Problem Statement:**  
In Chefland, everyone who earns strictly more than Y rupees per year, has to pay a tax to Chef. Chef has allowed a special scheme where you can invest any amount of money and claim exemption for it. You have earned X (X>Y) rupees this year. Find the minimum amount of money you have to invest so that you don't have to pay taxes this year.

🔗 Problem Link: ([https://www.codechef.com/learn/course/cpp-beginner/BC00BC09/problems/CSC02A](https://www.codechef.com/problems/TAXSAVING))

solution: 


```cpp
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t;
	cin>>t;
	while(t--){
	    int y,x;
	    cin>>x>>y;
	    cout<<x-y<<endl;
	}
	return 0;
}
