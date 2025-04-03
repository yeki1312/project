using System;

class Program
{
    static void Main(string[] args)
    {
        Console.Write("لطفا یک عدد وارد کنید: ");
        int num = int.Parse(Console.ReadLine());

        if (num % 7 == 0)
        {
            Console.WriteLine("Yes!");
        }
        else
        {
            int result = num * 3;
            Console.WriteLine("Result: " + result);
        }
    }
}
