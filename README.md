Emin Selim Ofluoğlu

& adres alır
* adresteki değer 

dip not: yapay zeka ile yapıldı ve düzenlendi

#include <iostream>
using namespace std;

int main() {

    int sayi1, sayi2;

    cout << "1. sayiyi girin: ";
    cin >> sayi1;

    cout << "2. sayiyi girin: ";
    cin >> sayi2;

    int* ptr1 = &sayi1;

    int* ptr2 = &sayi2;

    cout << "1. sayi: " << sayi1 << endl;

    cout << "1. sayinin adresi: " << &sayi1 << endl;

    cout << "2. sayi: " << sayi2 << endl;

    cout << "2. sayinin adresi: " << &sayi2 << endl;

    cout << "Toplam: " << *ptr1 + *ptr2 << endl;


    return 0;
}
