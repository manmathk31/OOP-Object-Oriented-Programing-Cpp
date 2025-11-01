## 🧮 Problem 7: Burgers

**Problem Statement:**  
Chef is fond of burgers and decided to make as many burgers as possible. Chef has A patties and B buns. To make 1 burger, Chef needs 1 patty and 1 bun. Find the maximum number of burgers that Chef can make.

🔗 Problem Link: https://www.codechef.com/problems/BURGERS

solution: 


```cpp
#include <iostream>
using namespace std;

int main() {
	
	int t,a,b,c;
	cin >>t;
	while(t--)
	{
	    cin >>a >>b;
	    if(a>b)
	    c=b;
	    else if(a<b)
	    c=a;
	    else 
	    c=b;
	    cout<<c;
	    cout<<"\n";
	}
	return 0;
}
