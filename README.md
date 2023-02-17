#include<iostream>
#include<string>
#include<limits>

using namespace std;


int main()
{
  int intMin = numeric_limits<int>::min();
  cout << intMin;
  int intMax = numeric_limits<int>::max();
  cout << intMax;
  
  
  short shortMin = numeric_limits<short>::min();
  cout << shortMax;
  short shortMax = numeric_limits<short>::max();
  cout << shortMax;
  
  
  long LongMax = numeric_limits<long>::max();
  cout << longMax;
  long LongMin = numeric_limits<long>::min();
  cout << longMin;
  
  
  unsigned int intA = numeric_limits<unsigned int>::min();
  cout << intA;
  unsigned int intB = numeric_limits<unsigned int>::max();
  cout << intB;

  
  unsigned short shortA = numeric_limits<unsigned short>::min();
  cout << shortA;
  unsigned short shortB = numeric_limits<unsigned short>::max();
  cout << shortB;
  
  
  unsigned long longA = numeric_limits<unsigned long>::min();
  cout << longA;
  unsigned long longB = numeric_limits<unsigned long>::max();
  cout << longB;
  

}
