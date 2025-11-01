## 🧮 Problem 11: Water Consumption

**Problem Statement:**  
Recently, Chef visited his doctor. The doctor advised Chef to drink at least 2000 ml of water each day. Chef drank X ml of water today. Determine if Chef followed the doctor's advice or not.

🔗 Problem Link: https://www.codechef.com/problems/WATERCONS

solution: 


```cpp

#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t;
	cin>>t;
	while(t--){
	    int w;
	    cin>>w;
	    if(w>=2000){
	        cout<<"YES\n";
	    } else{
	        cout<<"NO\n";
	    }
	}
	return 0;
}
