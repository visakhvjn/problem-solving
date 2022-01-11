Problem Link

`https://www.codechef.com/problems/CHOPRT`

Solution

```
#include <iostream>
using namespace std;

int main() {
    
    int t, a, b;
    
    cin >> t;
    
    for (int i = 0; i < t; i++) {
        cin >> a >> b;
        
        if (a < b) cout << "<";
        else if (a > b) cout << ">";
        else cout << "=";
        
        cout << endl;
        
    }
    
	return 0;
}
```