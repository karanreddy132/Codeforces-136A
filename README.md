# Codeforces-136A
#include <iostream>
 
using namespace std;

int main() {
    int n, m, arr[105];
    cin >> n;
    for (int i = 1; i <= n; i++) {
        cin >> m;
        arr[m] = i;
    }
    for (int i = 1; i <= n; i++) {
        cout << arr[i] << " ";
    }
}
