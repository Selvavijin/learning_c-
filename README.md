# learning_c++

![image](https://github.com/user-attachments/assets/76099c2d-4bff-4860-ba50-e70b3255b56d)

![image](https://github.com/user-attachments/assets/f826cdcf-0bcf-48e4-9fca-416db5c9b3c4)

![image](https://github.com/user-attachments/assets/0297eac5-027d-40e6-8747-b044f4dfe70f)

![image](https://github.com/user-attachments/assets/8fbfb7b2-d012-41c2-a6c7-ef7c057a8edf)

![image](https://github.com/user-attachments/assets/f3b9d2fb-0fbd-4a7a-ab4f-ee5439f6a899)

![image](https://github.com/user-attachments/assets/1cf2e709-8fb6-40fb-896a-fe8ff0ca8bd9)

![image](https://github.com/user-attachments/assets/d5b3355e-ce75-42aa-a557-84f9df497281)

![image](https://github.com/user-attachments/assets/0aa50451-b5ff-41e2-8270-d2f20a59b485)

![image](https://github.com/user-attachments/assets/8f913886-ecbf-4c2a-b2d9-1cd264f5bd01)

![image](https://github.com/user-attachments/assets/731b5a57-7748-4b6f-a2d7-f420dab7e11a)

![image](https://github.com/user-attachments/assets/005bf797-e996-4657-a5ea-5b02508ffb7d)

![image](https://github.com/user-attachments/assets/c48aa5ad-e396-4c70-aa7e-7f9b0a52b2f1)

![image](https://github.com/user-attachments/assets/fc2b3788-7c5c-4425-b447-3b0a8eda93af)

![image](https://github.com/user-attachments/assets/9e32fd80-8d6f-41b0-a00e-0a192180edb1)

![image](https://github.com/user-attachments/assets/88c5fe60-0a87-4490-9580-2e4a75e878e8)

![image](https://github.com/user-attachments/assets/93df61b2-1e80-482f-89c5-ab6869cadd73)

![image](https://github.com/user-attachments/assets/eeb2cb84-9ce4-4572-adde-2917cd9234c1)


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

Functions:

#include <iostream>

using namespace std;

void sayhello(string name) {
    string msg="Hello " ;
    cout << msg<< name;
}

int main() {
    sayhello("vijin") ;
}

Here we pass the parameters to the functions. Functions can also return the values. Let us see how to do that.

#include <iostream>

using namespace std;

int sayhello(int num) {
    int cube = num*num*num;
    return cube;
}

int main() {
    cout << sayhello(3) ;
}

![image](https://github.com/user-attachments/assets/d9722b9a-115c-41c6-a216-0658cc1e37c2)

