# task-4
#include<iostream>
using  namespace std;
int main()
{
    int num1,num2,sum,sub,mul,div;
    cout<<"enter the first number"<<endl;
    cin>>num1;
    cout<<"enter the second number"<<endl;
    cin>>num2;
    char op;
    cout<<"enter the operator"<<endl;
    cin>>op;
    switch(op)
    {
        case '+':
        sum=num1+num2;
        cout<<sum<<endl;
          break;
        case '-':
        sub=num1-num2;
        cout<<sub;
          break;
        case'*':
        mul=num1*num2;
          break;
        case'/':
        div=num1/num2;
          break;
        default:
        cout<<"error";
        
        break;
        
    
    }
}
