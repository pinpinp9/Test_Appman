# Test_Appman
using Microsoft.VisualBasic.CompilerServices;
using System;

namespace Test_Appman
{
    class Program
    {
        static void Main(string[] args)
        {
           
            //A
            Console.WriteLine("Please enter A");
            String A = Console.ReadLine();
            //Use function 
            Console.Write("The output is ");

          
            for (int i = 3; i < A.Length; i++)
            {
               
                    int a = 0;
                    a = a * 10 + ((int)A[i] - 48);

                Console.Write(a);
                
                }

                       
         
            Console.WriteLine("");
            Console.WriteLine("____________________");

            //B
            Console.WriteLine("Please enter B");
            String B = Console.ReadLine();
          
            Console.Write("The output is ");
            for (int j = 1; j < B.Length; j+=2)
            {
                int b = 0;
                b = b * 10 + ((int)B[j] - 48);
                Console.Write(B[j]);
               
            }
            Console.ReadLine();
        }
    }
}
