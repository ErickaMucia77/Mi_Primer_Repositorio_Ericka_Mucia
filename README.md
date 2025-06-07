#include <iostream>
using namespace std;
int main (){
string frutas frutas[5];
string nombre;
cout<<"BIENVENIDO USUARIO"<<endl;
cout<<"Ingrese su nombre";
cin>>nombre;
cout<<"Nombra 5 de tus frutas favoritas"<<nombre<<endl;
}
for(int i = 0; i<=4; i++){
cout<<"\n Ingrese la fruta" <<i+1<<":"<<endl;
cin>>frutas[i];
}

cout<<"Las frutas son muy importantes para nuestro organismo"<<endl;
cout<<"La "<<frutas[1]<<" es deliciosa"<<endl;
return 0;
}
