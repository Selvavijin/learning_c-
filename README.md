# learning_c++

String: 

  Here, 'find' function is used where 2 arguments can be passed. The first argument specifies the character or string that we need to find and the second argument specifies the index value from where we need to search.
#include <iostream>
using namespace std;
int main() {
    string name="selva vijin raj a";
    cout << name.find('a',8);
    return 0;
}
Output: 13

Substring function is used here. the first argument specifies the starting index of the substring and the second argument specifies the number of values we need from the specified index value.

#include <iostream>
using namespace std;
int main() {
    string name="selva vijin raj a";
    cout << name.substr(6,5);
    return 0;
}
Output: vijin

Here length function is used.

#include <iostream>
using namespace std;
int main() {
    string name="selva vijin raj a";
    cout << name.length();
    return 0;
}
Output: 17

Numbers: 

In numbers we can use functions like pow(a,b), sqrt(x),round(a), ceil(a)[Here, even if 'a' is 4.1, it gets rounded off to 5], floor(a)[Here, even if 'a' is 4.8, it gets rounded off to 4], fmax(a,b) and fmin(a,b) gives us the bigger and smaller number respectively   after including '#include <cmath>'.

getline():

Till we get the input string as a word. To get it as a line, we use this command.

#include<iostream>

using namespace std;

int main()
{
    cout<<"What is your name?";
    string name;
    getline(cin,name);
    cout << "I am "<<name;
    return 0;
}

Arrays:

Here we can either specify the size inside the variable name or we can simply use the square brackets. 

#include <iostream>

using namespace std;

int main() {
    int numbers[10] = {1,2,3,4,5,6,7};
    numbers[9]=7;
    cout << numbers[9]<<endl;
    cout << numbers[8];
}

Output: 7  0

