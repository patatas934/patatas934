// Created on iPad.

#include <iostream>
using namespace std;

void start(){
    cout<<"To pehnidi jekina";
}

void exit(){
    cout<<"To paihnidi telionei !";
}



int main() {
    char ekinisi;
    
    cout << "Kalos irthare sto pehnidi mas !!! \n";
    cout << "Gia na jekinsiete to tichu press :[s(start)/e(exit)] \n";
    cin>> ekinisi;

    switch (ekinisi){

        case 's':
            start();
            break;

        case 'e':
            exit();
            break;    
    }

    return 0;
}