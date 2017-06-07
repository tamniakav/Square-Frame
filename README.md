using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Square_Frame
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());

            Console.Write("+ ");
            for (int i = 0; i < n - 2; i++)
            {
                Console.Write("{0} ", new string('-', 1));
            }
            Console.WriteLine("+ ");

            for (int i = 0; i < n - 2; i++)
            {
                Console.Write("| ");
                for (int j = 0; j < n - 2; j++)
                {
                    Console.Write("{0} ", new string('-', 1));
                }
                Console.WriteLine("| ");
            }

            Console.Write("+ ");
            for (int i = 0; i < n - 2; i++)
            {
                Console.Write("{0} ", new string('-', 1));
            }
            Console.WriteLine("+ ");
        }
    }
}

