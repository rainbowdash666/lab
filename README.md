#include <iostream>
    using namespace std;

    int main()
    {
        int a, b, p, s;
        setlocale(LC_ALL, "Russian");
        cout << "Первый номер" << endl;
        cout << "Введите ширину " << endl; cin >> a;
        cout << "Введите длинну " << endl; cin >> b;
        p = 2 * (a + b);
        s = a * b;
        cout << "Площадь равна " << s << endl;
        cout << "Периметр равен " << p << endl;
        cout << " " <<endl;



        double d, l;
        const double pi = 3.14; 
        cout << "Второй номер" << endl;
        cout << " Введите диаметр " << endl;
        cin >> d;
        l = pi * d;
        cout << "Длинна окружности равна " << l<< endl;
        cout << " " << endl;



        double q, w, sr;

        cout << "Третий номер" << endl;
        cout << "Введите число" << endl;
        cin >> q >> w;
        sr = (q + w) / 2;
        cout << "Среднее арифметическое " << sr<< endl;
        cout << " " << endl;


        double h, k,o,e,f,u;
        cout << "Четвёртый номер" << endl;
        cout << "Введите два ненулевых числа" << endl;
        cin >> h >> k;
        o = h * h + k * k;
        e = h * h - k * k;
        f = (h * h) * (k * k);
        u = (h * h) / (k * k);

        cout << "Сумма квадратов равна " << o<< endl;
        cout << "Разность квадратов равна " << e << endl;
        cout << "Произведение квадратов равна " << f << endl;
        cout << "Частное квадратов ранва " << u << endl;
        cout << " " << endl;


        double c,x,j,g,m, y;
        cout << "Пятый номер" << endl;
        cout << "Введите два числа" << endl;
        cin >> m >> y;
        c = abs(m) + abs(y);
        x = abs(m) - abs(y);
        j = abs(m) * abs(y);
        g = abs(m) / abs(y);
        cout << "Сумма равна " << c << endl;
        cout << "Разность равна " << x << endl;
        cout << "Произведение равно " << j << endl;
        cout << "Частное ранво " << g << endl;
        cout << " " << endl;

    }
