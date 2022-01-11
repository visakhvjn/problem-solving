Problem Link

`https://www.codechef.com/problems/FLOW008`

Solution

```
#include <iostream>
using namespace std;

int main() {
	
	int t, n;
	
	cin >> t;
	
	for (int i = 0; i < t; i++) {
	    cin >> n;
	    
	    if (n < 10) cout << "Thanks for helping Chef!";
	    else cout << "-1";
	    
	    cout << endl;
	}
	
	return 0;
}
