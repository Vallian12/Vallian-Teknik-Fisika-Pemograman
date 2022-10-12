# Vallian-Teknik-Fisika-Pemograman

// NAMA		: Vallian Siddhijaya Kwee
// NRP		: 5009221029
// Jurusan	: Teknik Fisika

#Define SUDUT 45
#Define GRAVITASI 10

#include <iostream>
#include <cmath>
using namespace std;

int main() 
{
    float V, V0; //V merupakan kecapatan tangesial dan V0 merupakan kecepatan awal
    float X // X merupakan jarak terjauh
    
    std :: cin >> V;
        
        if (V<=11);
    {
        V0 = V - 1;
    }
        if (V<=23);
    {
        V0 = V - 3;
    }
        else (V<=35);
    {
        V0 = V - 5;
    }
    // X = 1 + (V0^2 * sin (2*SUDUT) / GRAVITASI)
    X = 1 + ( V0^2 / 10 )
    std :: cout << X << "  " << V << endl;  
    return 0;
}
