using System;

class Program
{
    static void Main(string[] args)
    {
        Console.Write("لطفا یک عدد وارد کنید: ");
        int num = int.Parse(Console.ReadLine());

        if (num < 10 && num % 2 == 0)
        {
            Console.WriteLine("true");
        }
    }
}
