#include <iostream>
#include <math.h>
using namespace std;
int main()
{ 
   float radio, altura, volumen;
   double nota;
   do {
      cout<<"1.-menu"<<endl;
      cout<<"2.-volumen del cilindro"<<endl;
      cout<<"3.-notas";
      cout<<"elija una opcion";
      cout<<"salir";
      
      switch (opcion)
      case 1:
      cout<<"ingrese el radio:";
      cin>>radio;
      cout<<"ingrese la altura:";
      cout>>altura;
      volumen=3.141516*por(radio,2)*altura;
      cout<<"el volumen del cilindro es:"<<volumen;
      break;
      case 2:
      cout<<"ingrese la nota:";
      cin>>nota;
      if(nota>51){
          cout<<"nota aprobada";
          else
             cout<<"reprobado";
             break;
              default:
              cout<<"opcion no valida"
   }

    return 0;
}
