// highest-number
//user will put three numbers and the output will be the highest number using function;

#include <iostream>
using namespace std;

void largest(int a, int b, int c);


int main(int argc, const char * argv[]) {
    int num1,num2,num3;
  cout<<"enter three numbers";
    cin>>num1>>num2>>num3;
  
    largest(num1,num2,num3);
    
    return 0;
}
void largest(int num1, int num2,int num3)
{
    if(num1>num2&& num1>num3)
    {
        cout<<num1<<" is the largest number";
    }
    else if (num2>num1&& num2>num3)
    {
        cout<<num2<<"is the largest number";
    }
    else {
        cout<<num3<<" is the largest number";
    }
    

}
