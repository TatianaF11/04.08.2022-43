//void Zadacha43()
{
    //Задача 43: Напишите программу, которая найдёт точку пересечения двух прямых, заданных уравнениями y = k1 * x + b1, y = k2 * x + b2; значения b1, k1, b2 и k2 задаются пользователем.
    //b1 = 2, k1 = 5, b2 = 4, k2 = 9 -> (-0,5; -0,5)
    int k1 = 0;
    int b1 = 3;
    int k2 = 1;
    int b2 = 2;
    double x;
    double y;

    if (k1 != k2)
    {
        x = (b2 - b1)/(k1-k2);
        y = k1 * x + b1;
        Console.WriteLine($"Точка пересечения прямых ({x}, {y})");
    }
    else
    {
        Console.WriteLine("Прямые параллельны");
    }

}
//Zadacha43();
