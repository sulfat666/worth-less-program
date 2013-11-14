worth-less-program
==================

..
#include <cstdlib>
#include <iostream>
#include <math.h>
#include <iomanip>
using namespace std;

int main(int argc, char *argv[])
{
    double tal1, tal2, summa, svar, ja ;
    
    cout<<"hej!! \n Skriv in två tal här!!: \n\n";
    
    cin>>tal1;
    cin>>tal2;
    
    tal1 + tal2 == summa;
    
    cout<<"vill du addera dom?\n";
    cin>>svar;
    if( svar == ja){
      cout<<summa;      
    }
    else {
      cout<<"fuck you!!!"<<summa<<"\n\n";   
    }         
  
    system("PAUSE");
    return EXIT_SUCCESS;
}
