# simple-calc
This can perfrom only simple calculations
#include<iostream>
using namespace std;
int main ()
{
	int num1,num2;
	char op;
	cout<<"enter the both numbers :";
	cin>>num1>>num2;
	cout<<"enter the opretors (+,-,*,/,%) :";
	cin>>op;
	switch(op)
	{
		case '+':
			cout<<num1<<"+"<<num2<<"="<<num1+num2;
			break;
		case '-':
			cout<<num1<<"-"<<num2<<"="<<num1-num2;
			break;
		case '*':
			cout<<num1<<"*"<<num2<<"="<<num1*num2;
			break;
		case'/':
		if(num2!=0){
		    cout<<num1<<"/"<<num2<<"="<<num1/num2;}
		else{
		    cout<<"divisionby zero is not allowed";}
		    break;
		default:
			cout<<"plzz enter from this opretors +,-,*,/,";
			break;
	}
	return 0;
	
}
