# Cycle_While
#include <iostream>
using namespace std;
int main()
{
    setlocale(LC_ALL, "Russian");
    int var1,a;
    cout << "Введите число: " << endl;
    cin >> var1;
    cout << "Введите кол-во кругов для цикла \n " << "Примечание: \n" << "Кол-во кругов должно быть строго больше чем число" << endl;
    cin >> a;
    while (var1 < a) // Пока var1 меньше "a"
    {
        if (var1 == 1) // Если var1 = 1 выводится "Первый круг" 
        {
            cout << "Первый круг" << endl;
        }
        else if (var1 < 5) // Иначе если var1 меньше 5 выводится "(Значение переменной var1) Круг"
        {
            cout << var1 << " Круг" << endl;
        }
        else if (var1 >= 5) // Иначе если var1 ,больше или равно 5 выводится "(Значение переменной var1) Кругов"
        {
            cout << var1 << " Кругов" << endl;
        }
        var1++; // увеличение переменной на 1
    }

}

