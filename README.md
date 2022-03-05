# Hafta-7-ödevim




#include <iostream>
using namespace std;
int sayi=2;
void fonksiyon1()
{
     sayi = 5;
}
void fonksiyon2()
{
    int sayi = 7;
    }
int main()
{ fonksiyon1();
fonksiyon2();
cout << sayi;
}

     EKRANA 5 YAZISI ÇIKIYOR
     
     
     
     
     
    
 #include<iostream>

using namespace std;
int main()
{
  int sayi;
  int sayac=0;
  cout<<"bir sayi giriniz:";

  cin>>sayi;

 for(int e=2; e<sayi; e++)
     {
      if(sayi % e == 0)
         {
          sayac++;
          break;
         }
     }
  if(sayac == 0)
     {
      cout<<"asaldır."<<endl;
     }
 else
      cout<<"asal değildir."<<endl;
 return 0;
}
                                   
                                   
                                   
                                   
 #include <iostream>
using namespace std;
int main()
{

	int x,y;
	cout<<"1. Sayiyi Gir : ";
	cin >> x;
	cout<<"2. Sayiyi Gir : ";
	cin >> y;
	cout<<"Bolum : "<<x/y<<endl;
	cout<<"Kalan : "<<x%y;
	return 0;
}
                                  
                                   
                                   
                                   
