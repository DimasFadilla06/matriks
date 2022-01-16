# matriks

#include <iostream>

using namespace std;

int main()
{
    //matriks
    
        int i, j, MAX;

        cout<< "masukkan jumlah yang di inginkan :";cin>> MAX;
        cout<< "=================================="<<endl;

        for (i = 0; i <= MAX; i++) {
        for (j = 0; j <= i; j++) {
        cout <<" * ";
        }
        cout << endl;
        }
    return 0;
}
