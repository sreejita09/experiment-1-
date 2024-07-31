# Experiment 1 
AIM: To install Visual Studio Code and writing a program to print hello world, and calculator program 

Theory: VS code is a code editor that allows you to run all types of programs and codes if the suitable extensions are added. In the codes, MinGW is used to add the c++ extension
printing hello world uses the "cout" character output and the calculator program uses the sum(+), difference(-), multiplication(*), division(/) arithmetic operators.
'''
Codes: 
'''
1. hello world:

'''
#include <iostream>
'''
using namespace std;
'''

int main() 
'''
{
   cout << "Hello World"; 
   return 0;
}

'''
 OUTPUT: 

 ![image](https://github.com/user-attachments/assets/c25720e4-d66f-4d80-90b3-a679328dbb1d)


2. Calculator:
#include<iostream>
using namespace std;

int main()
{
    int a,b,sum=0, diff, mult, div ;
    cout<<"enter a number a: ";
    cin>>a;
    cout<<"enter a number b: ";
    cin>>b; 

    sum=a+b;
    cout<<"sum is: "<<sum<<endl; 

    diff=a-b; 
    cout<<"diff is: "<<diff<<endl;

    mult=a*b;
    cout<<"mult is: "<<mult<<endl;

    div=a/b;
    cout<<"division is: "<<div<<endl; 

    return 0;
}

OUTTPUT:
![image](https://github.com/user-attachments/assets/868e576e-ead6-4799-b318-75ab69c6864a)
