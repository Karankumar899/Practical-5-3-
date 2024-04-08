# Practical-5-3-

#include<iostream>

using namespace std;

class Employee{
    public:
      int Number;
   string EN;
   double Basic;
   double DA;
   double IT;
   double NS;
};

int main()
{
      Employee e1;

      e1.Number = 9584732147;
      e1.EN = "Karan Kumar";
      e1.Basic = 45;
      e1.DA = 24;
      e1.IT = 22;
      e1.NS = 35000;

     cout << "Employee Number = " << e1.Number<<endl;
     cout << "Employee Name = " << e1.EN<<endl;
     cout << "Employee Basic = " << e1.Basic<<endl;
    cout << "Employee DA = " << e1.DA<<endl;
    cout << "Employee IT = " << e1.IT<<endl;
    cout << "Employee NS = " << e1.NS<<endl;


    return 0;
}
