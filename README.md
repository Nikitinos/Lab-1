# Lab-1
using System;

namespace ConsoleApp3
{
    class Program
    {
        static int DecimalPart(double number)
        {
            Console.WriteLine("LabOnee");
            int d = 0;
            return d = int.Parse(number.ToString()[number.ToString().IndexOf(',') + 1].ToString());
        }
        static void Main(string[] args)
        {
            Console.WriteLine(DecimalPart(27.3198));
            Console.ReadKey();

        }
    }
}
