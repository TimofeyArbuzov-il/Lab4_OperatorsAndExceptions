using System;

class Program
{
    static void Main()
    {
        Console.Write("Введите номер дня в году (1–365): ");
        int dayNumber = int.Parse(Console.ReadLine());

        int[] daysInMonths = { 31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31 };
        string[] monthNames = {
            "Января", "Февраля", "Марта", "Апреля", "Мая", "Июня",
            "Июля", "Августа", "Сентября", "Октября", "Ноября", "Декабря"
        };

        int month = 0;
        while (dayNumber > daysInMonths[month])
        {
            dayNumber -= daysInMonths[month];
            month++;
        }

        Console.WriteLine($"Это {dayNumber} {monthNames[month]}.");
    }
}
