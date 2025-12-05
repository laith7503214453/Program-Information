# Program-Information
In this program you will enter your information like: name, age, toll, passing grade, blood type and the success
#include<iostream>
using namespace std;

int main(){

    string Name;
    int Age;
    float Toll;
    double PG;
    char BT;
    bool S;

    cout<<"Enter your Name: ";
    cin>>Name;
    cout<<"Enter your Age: ";
    cin>>Age;
    cout<<"Enter your Toll: ";
    cin>>Toll;
    cout<<"Enter your PG: ";
    cin>>PG;
    cout<<"Enter your Blood Type: ";
    cin>>BT;
    cout<<"Enter your Success (1 for true , 0 for false): ";
    cin>>S;

    cout<<"****** User Information *******"<<endl;
    cout<<"Name: "<<Name<<endl;
    cout<<"Age: "<<Age<<endl;
    cout<<"Toll: "<<Toll<<endl;
    cout<<"Rsult: "<<PG<<endl;
    cout<<"Blood Type: "<<BT<<endl;
    cout<<"Success: "<<S<<endl;

    return 0;

}
