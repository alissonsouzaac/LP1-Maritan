# LP1-Maritan
#include <iostream>
#include "Data.h"
using namespace std;

int main()
{
    Data data1 = Data(31,12,2018);
    Data *data2 = new Data(30,15,2018);

    data2->avancarDia();
    cout << "Datas: " << data2->dia <<"/"<< data2->mes<<"/"<<data2->ano<< endl;
    return 0;
}
