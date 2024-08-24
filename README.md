# Arrays-and-strings
# Aim:   
To use and implement C++ Arrays and string.
# Software Used: 
Visual Studio Code
# Theory: 
## Arrays:
An array in C++ is a collection of elements of the same data type, stored in contiguous memory locations. Arrays provide a way to store multiple values under a single variable name, accessible via an index.
### Syntax:
`data_type array_name[array_size];`
```cpp
#include<iostream>
using namespace std;
int main()
{
    int x[6] = {1,4,7,8,3,9};
    int i;
    for (i=0;i<6;i++)
    {
        cout<<x[i]<<endl;
    }
}
```
## Strings:
In C++, a string is an array of characters terminated by a null character ('\0'). Strings in C++ can be handled using either C-style strings (character arrays) or the std::string class from the Standard Library.
### Syntax:
`char str[10] = "Hello";`
```cpp
#include<iostream>
using namespace std;
int main()
{
    char str1[4] = "C++";
    char str2[] = {'s','+','+','\0'};
    string str3 = "C++";

    cout<<str1<<endl<<str2<<endl<<str3;
}
```

