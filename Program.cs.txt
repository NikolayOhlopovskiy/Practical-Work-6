using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp27
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //try
            //{
            //    Console.Write("x= ");
            //    int x = int.Parse(Console.ReadLine());
            //    int y = x<0?x+1:x-1;
            //    Console.WriteLine($"y= {y}");
            //}
            //catch (Exception ex)
            //{
            //    Console.WriteLine($"Исключение: {ex.Message}");
            //    Console.WriteLine($"Метод: {ex.TargetSite}");
            //    Console.WriteLine($"Трассировка стека: {ex.StackTrace}");
            //}
            //Console.ReadLine();

            //Задача 1.Используя двузначное случайное число, вывести на экран информацию о четности или нечетности этого числа с использованием тернарной операции.
            //Random rnd = new Random();
            //int chislo = rnd.Next(10, 99);
            //Console.WriteLine($"Случайное число = {chislo}");
            ////if (chislo % 2 == 0)
            ////{
            ////    Console.WriteLine($"{chislo}-четное");
            ////}
            ////else
            ////{
            ////    Console.WriteLine($"{chislo}-не четное");
            ////}
            //string random = (chislo % 2 == 0) ? "четное" : "нечетное";
            //Console.WriteLine($"Число {chislo}-{random}");
            //Console.ReadLine();


            //try
            //{
            //    //Задача 2.Дано целое число n, указывающее номер дня недели от 1 до 7.По указанному номеру n вывести название соответствующего дня недели. 
            //    Console.Write("Номер дня недели: ");
            //    byte day = byte.Parse(Console.ReadLine());
            //    switch (day)
            //    {
            //        case 1:Console.WriteLine("Понедельник");
            //            break;
            //        case 2:Console.WriteLine("Вторник");
            //            break;
            //        case 3:
            //            Console.WriteLine("Среда");
            //            break;
            //        case 4:
            //            Console.WriteLine("Четверг");
            //            break;
            //        case 5:
            //            Console.WriteLine("Пятница");
            //            break;
            //        case 6:
            //            Console.WriteLine("Суббота");
            //            break;
            //        case 7:
            //            Console.WriteLine("Воскресенье");
            //            break;
            //        default:Console.WriteLine("Нет такого");
            //            break;
            //    }
            //}
            //catch (Exception ex)
            //{
            //    Console.WriteLine($"Исключение: {ex.Message}");
            //    Console.WriteLine($"Метод: {ex.TargetSite}");
            //    Console.WriteLine($"Трассировка стека: {ex.StackTrace}");
            //}
            //Console.ReadLine();

            //Задача 3.Используя случайное число в диапазоне от 1 до 7, вывести на экран название дня недели.
            //Random rnd = new Random();
            //int chislo = rnd.Next(1, 7);
            //Console.WriteLine($"Случайное число = {chislo}");
            //switch (chislo)
            //{
            //    case 1: Console.WriteLine("Понедельник"); break;
            //    case 2: Console.WriteLine("Вторник"); break;
            //    case 3: Console.WriteLine("Среда"); break;
            //    case 4: Console.WriteLine("Четверг"); break;
            //    case 5: Console.WriteLine("Пятница"); break;
            //    case 6: Console.WriteLine("Суббота"); break;
            //    case 7: Console.WriteLine("Воскресенье"); break;
            //}
            //Console.ReadLine();


            //try
            //{
            //    //Задача 4.По номеру месяца вывести название времени года.
            //    Console.Write("Номер месяца: ");
            //    byte month = byte.Parse(Console.ReadLine());
            //    switch (month)
            //    {
            //        case 12:
            //        case 1:
            //        case 2:
            //            Console.WriteLine("Зима");
            //            break;
            //        case 3:
            //        case 4:
            //        case 5:
            //            Console.WriteLine("Весна");
            //            break;
            //        case 6:
            //        case 7:
            //        case 8:
            //            Console.WriteLine("Лето");
            //            break;
            //        case 9:
            //        case 10:
            //        case 11:
            //            Console.WriteLine("Осень");
            //            break;
            //        default:
            //            Console.WriteLine("Нет такого");
            //            break;
            //    }
            //}
            //catch (Exception ex)
            //{
            //    Console.WriteLine($"Исключение: {ex.Message}");
            //    Console.WriteLine($"Метод: {ex.TargetSite}");
            //    Console.WriteLine($"Трассировка стека: {ex.StackTrace}");
            //}
            //Console.ReadLine();


            //Задача 5.Дан признак транспортного средства: a – автомобиль, в – велосипед, м - мотоцикл, с – самолет, п – поезд.Вывести на экран максимальную скорость транспортного средства в зависимости от введенного признака
            //    Console.Write("Введите транспорт:");
            //    char transport = char.Parse(Console.ReadLine());
            //    switch (transport)
            //    {
            //        case 'a': Console.WriteLine("Максимальная скорость автомобиля 200 км/ч"); break;
            //        case 'в': Console.WriteLine("Максимальная скорость велосипеда 40 км/ч"); break;
            //        case 'м': Console.WriteLine("Максимальная скорость мотоцикла 200 км/ч"); break;
            //        case 'с': Console.WriteLine("Максимальная скорость самолета 360 км/ч"); break;
            //        case 'п': Console.WriteLine("Максимальная скорость поезда 350 км/ч"); break;
            //        default: Console.WriteLine("Нет такого вырианта");  break; 
            //    }
            //Console.ReadLine();


            //Задача 6.Вывести название предмета по введенной первой букве: ф – физика, м – математика, и – история, г – география, б – биология.
            //Console.Write("Школьный предмет: ");
            //char subject = char.Parse(Console.ReadLine());
            //switch (subject)
            //{
            //    case 'ф': Console.WriteLine("Физика"); break;
            //    case 'м': Console.WriteLine("Математика"); break;
            //    case 'и': Console.WriteLine("История"); break;
            //    case 'г': Console.WriteLine("География"); break;
            //    case 'б': Console.WriteLine("Биология"); break;
            //    default: Console.WriteLine("Нет такого вырианта"); break;
            //}
            //Console.ReadLine();



            //Задача A
            //Console.Write("Опишите фигуру");
            //char figure=char.Parse(Console.ReadLine());
            //switch(figure)
            //{
            //    case 'к': case 'К': Console.Write("r= ");
            //        double r = double.Parse(Console.ReadLine());
            //        c = 2*Math.PI*r;
            //        Console.WriteLine
            //}
            //Console.Read();
        }
    }
}
