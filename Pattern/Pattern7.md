## Description
In this code you will find how you can make * pattern by using For loop

## Code 
```cpp

#include<iostream>
using namespace std;
int main()
{
int n, s, i, j;
cout << "Enter number of rows: ";
cin >> n;
for(i = 0; i <= n; i++)
{
for(s = n; s > i; s--)
cout << " ";
for(j=0; j<i; j++)
cout << "* ";
cout << "\n";
}
for(i = 1; i < n; i++)
{
for(s = 0; s < i; s++)
cout << " ";
for(j = n; j > i; j--)
cout << "* ";
// ending line after each row
cout << "\n";
}
return 0;
}
```
## Input
```
N = 4
```
## Output
```
   *
  * * 
 * * *
* * * *
 * * *
  *  
  
```