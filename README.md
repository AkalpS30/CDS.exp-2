# CDS.exp-2
## Aim:
_**To study and implement C++ Program Structure (Data Types).**_

## **Software:** 
Microsoft VSCode


## Theory:
_Data types define the type of data that a variable can hold, such as `integers`, `floating-point numbers`, `characters`, and more. We can also find the size of these data types by using `sizeof` keyword. These data types can be subdivided into three parts which are as follows_
+ **Basic Datatype**
+ **Derived Datatype**
+ **User-Defined Datatype**


 Storage class in C++ determines the characteristics of a variable.
C++ has 5 types of storage classes which are as follows:
+ **Auto**
+ **Extern**
+ **Mutable**
+ **Register**
+ **Static**


## Code: 2A
```
//AKALP SARKAR
//E&TC B2
//EXP 2A
//23070123116
#include <iostream>
using namespace std;
int main() {
    cout << "size of char: " << sizeof(char) << " byte" << endl;
    cout << "size of int: " << sizeof(int) << " byte" << endl;
    cout << "size of float: " << sizeof(float) << " byte" << endl;
    cout << "size of double: " << sizeof(double) << " byte" << endl;
    cout << "size of short int: " << sizeof(short int) << "byte" << endl;
    cout << "size of long int: " << sizeof(long int) << "byte" << endl;
    cout << "size of unsigned char: " << sizeof(unsigned char) << "byte" << endl;
    cout << "size of signed char: " << sizeof(signed char) << "byte" << endl;
    cout << "size of unsigned int: " << sizeof(unsigned int) << "byte" << endl;
    cout << "size of signed int: " << sizeof(signed int) << "byte" << endl;
    cout << "size of unsigned long int: " << sizeof(unsigned long int) << "byte" << endl;
    cout << "size of signed long int: " << sizeof(signed long int) << "byte" << endl;
    cout << "size of unsigned short int: " << sizeof(unsigned short int) << "byte" << endl;
    cout << "size of signed short int: " << sizeof(signed short int) << "byte" << endl;
    cout << "size of unsigned long long int: " << sizeof(unsigned long long int) << "byte" << endl;
    cout << "size of bool: " << sizeof(bool) << "byte" << endl;
    return 0;
}
```
## Output 2a
![output2a](https://github.com/user-attachments/assets/80f9e7b4-a312-4e70-8eca-730d99438c33)
## Code: 2B
```
//KANWALJEET SINGH
//ENTC B2
//EXP 2B
//23070123124
#include<iostream>
using namespace std;
int main() {
    int a;
    char b;
    signed char c;
    unsigned char d;
    float e;
    double f;
    long double g;
    bool h;
    cout<<"Enter an integer: ";                     
    cin>>a;
    cout<<"Size of int is:"<<sizeof(a)<<"\n";        

    cout<<"Enter a character: ";                   
    cin>>b;
    cout<<"Size of char is:"<<sizeof(b)<<"\n";        

    cout<<"Enter a character: ";                    
    cin>>c;
    cout<<"Size of signed char is:"<<sizeof(c)<<"\n";     

    cout<<"Enter a character: ";                        
    cin>>d;
    cout<<"Size of unsigned char is:"<<sizeof(d)<<"\n";  

    cout<<"Enter a number: ";                             
    cin>>e;
    cout<<"Size of float is:"<<sizeof(e)<<"\n";           
    

    cout<<"Enter a number: ";                            
    cin>>f;
    cout<<"Size of double is:"<<sizeof(f)<<"\n";         

    cout<<"Enter a number: ";                           
    cin>>g;
    cout<<"Size of long double is:"<<sizeof(g)<<"\n";   

    cout<<"Enter a bool value: ";                      
    cin>>h;
    cout<<"Size of bool is:"<<sizeof(h)<<"\n";            
return 0;
}
```
## Output 2b
![output2b](https://github.com/user-attachments/assets/82ce24b3-7071-46e3-be56-00091d19d007)
## Code: 2C
```
//KANWALJEET SINGH
//ENTC B2
//EXP 2C
//23070123124
#include<iostream>
using namespace std;

int main() {
    int a;
    cout<<"Enter a number: ";                       
    cin>>a;
    cout<<"\nInteger= "<<a<<" and size is "<<sizeof(a)<<" bytes.";  

    register int b;
    cout<<"\nEnter a number: ";                                     
    cin>>b;
    cout<<"\nRegister= "<<b<<" and size is "<<sizeof(b)<<" bytes.";   

    static int d;
    cout<<"\nEnter any number: ";                                      
    cin>>d;
    cout<<"\nStatic= "<<d<<" and size is "<<sizeof(d)<<" bytes.";      

    return 0;
}
```
## Output 2c
![output2](https://github.com/user-attachments/assets/89d77a50-99ca-4ddf-ae1c-434dc0372fea)

## Conclusion:
By studying and implementing various data types in C++, you build a strong foundation in how the language handles data and memory. This knowledge is essential for writing efficient and effective C++ programs. Practicing with real-world examples and exploring advanced concepts 
like dynamic memory allocation will deepen your understanding and prepare you for more complex programming challenges.
