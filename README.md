# find-smallest-number
enter 3 number and find smallest
using System;
using System.Collections.Generic;
using System.Text;

namespace smallest_number_find
{
    internal class Program
    {
        static void Main(string[] args)
        {
            
            Console.WriteLine("Enter first Number:");
            int a = int.Parse(Console.ReadLine());
            Console.WriteLine("Enter Second Number:");
            int b = int.Parse(Console.ReadLine()); ;
            Console.WriteLine("Enter Third Number:");
            int c = int.Parse(Console.ReadLine());

            if (a < b && a < c)
                Console.WriteLine("First Number is smallest" + a);
            else if (b < c && b < a)
                Console.WriteLine("Second Number is smallest" + b);
            else
                Console.WriteLine("Third Number is smallest" + c);
        }
    }
}
