## 🧮 Problem 8: Chef Plays Ludo

**Problem Statement:**  
Chef is playing Ludo. According to the rules of Ludo, a player can enter a new token into the play only when he rolls a 6 on the die. In the current turn, Chef rolled the number X on the die. Determine if Chef can enter a new token into the play in the current turn or not.

🔗 Problem Link: https://www.codechef.com/problems/LUDO

solution: 


```cpp
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t,x;
	cin>>t;
	while(t--)
	{
	    cin>>x;
	    if(x==6)
	    cout<<"YES"<<endl;
	    else
	    cout<<"NO"<<endl;
	}
	return 0;
}
