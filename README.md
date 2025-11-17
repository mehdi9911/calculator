#include <iostream.h>
using namespace std;
int main()
{
	double num1,num2;
	char op;
	cout<<"enter first number"<<endl;
	cin>>num1;
	cout<<"enter a the operator like +,-,/,*"<<endl;
	cin>>op;
	cout<<"enter second number"<<endl;
	cin>>num2;
	if(op == '+'){
		cout<<"result is"<<num1 + num2<<endl;
	}
		if(op == '-'){
		cout<<"result is"<<num1 - num2<<endl;
	}
		if(op == '/'){
		cout<<"result is"<<num1 / num2<<endl;
	}
		if(op == '*'){
		cout<<"result is"<<num1 * num2<<endl;
	}
	else
	   cout<<"enter a corract operator"<<endl;
  return 0;
}
