#include <iostream>
using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");

    int a, b, p, s;
    const double pi = 3.14;
    cout <<"Первый номер" << endl;

    cout << "Введите ширину "<< endl; cin >> a ;
    cout << "Введите длинну " << endl; cin>> b;
    p = 2 * (a + b);
    s = a * b;
    cout << "Площадь равна " << s << endl;
    cout << "Периметр равен " << p << endl;
}


#include <iostream>
using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");

    int d, l;
    const double pi = 3.14;
        cout << "Второй номер" << endl;
    cout << " Введите диаметр " <<endl;
    cin >> d;
    l = pi * d;
    cout << "Длинна окружности равна " << l;
}


