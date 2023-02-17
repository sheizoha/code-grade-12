#include<iostream>
#include<string>
#include<limits>

using namespace std;


int main()
{
  int intMin = numeric_limits<int>::min();
  cout << intMin;
  cout << "\n";
  int intMax = numeric_limits<int>::max();
  cout << "\n";
  cout << intMax;
  
  
  short shortMin = numeric_limits<short>::min();
  cout << shortMin;
  cout << "\n";
  short shortMax = numeric_limits<short>::max();
  cout << "\n";
  cout << shortMax;
  
  
  long longMax = numeric_limits<long>::max();
  cout << longMax;
  cout << "\n";
  long longMin = numeric_limits<long>::min();
  cout << longMin;
  cout << "\n";

  
  
  unsigned int intA = numeric_limits<unsigned int>::min();
  cout << intA;
  cout << "\n";
  unsigned int intB = numeric_limits<unsigned int>::max();
  cout << intB;
  cout << "\n";


  
  unsigned short shortA = numeric_limits<unsigned short>::min();
  cout << shortA;
  cout << "\n";
  unsigned short shortB = numeric_limits<unsigned short>::max();
  cout << shortB;
  cout << "\n";
  
  
  unsigned long longA = numeric_limits<unsigned long>::min();
  cout << longA;
  cout << "\n";
 
  unsigned long longB = numeric_limits<unsigned long>::max();
  cout << longB;
  cout << "\n";

 
 // exersize 3 attempt 2
 //slayyyyyyyyyyy

  string name;
  char hand;
  short age;
  string phoneNumber;


  cout << "\n";
  cout << "\n";
 
  cout << "enter your name \n";
  getline(cin, name);
  cout << "\n";
 
  cout << "Enter Handedness (L/R/A) \n";
  cin >> hand;
  cout << "\n";
 
  cout << "Enter your age \n";
  cin >> age; 
  cout << "\n";
 
  cout << "Enter your phone number (Canada) +1 \n";
  cin >> phoneNumber;
  
  cout << "\n";
  cout << "\n";
  cout << "\n";

  cout << " ______________________\n";
  cout << "|                     | \n";
  cout << "|          " << name <<"| \n";
  cout << "|          " << age <<"         | \n";
  cout << "|          " << hand <<"          | \n";
  cout << "|        +1" << phoneNumber <<" | \n";
  cout << "|_____________________|\n";

}
