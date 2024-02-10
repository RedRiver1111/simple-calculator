# simple calculator
#include <iostream>
#include <cmath>
#include <string>





int main(){


std::string operation ;
double firstNum;
double secendNum;

/* require a develop to one step 
std::cout << "enter the the first number : " <<std::endl;
std::cin>>firstNum;
std::cout<<"enter the operation [+,*,-,/]"<<std::endl;
std::cin>>operation;
std::cout<<"enter the secend number"<<std::endl;
std::cin>>secendNum;*/

//the new one step 
std::cout<<"enter your equation>> "<<std::endl;
std::cin>>firstNum,operation,secendNum;


if (operation == "+"){ 
 std::cout<<"the answer is : "<<firstNum + secendNum<<std::endl; }
else if (operation == "-"){ 
 std::cout<<"the answer is : "<<firstNum - secendNum<<std::endl; }
else if (operation == "/"){ 
 std::cout<<"the answer is : "<<firstNum / secendNum<<std::endl; }
else if (operation == "*"){ 
 std::cout<<"the answer is : "<<firstNum * secendNum<<std::endl; }
else{ 
 std::cout<<"invalid operation data"<<std::endl;}


return 0;
}
  
  
