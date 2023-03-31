using System;

class Program {
    static void Main(string[] args) {
        Console.Write("Enter the first number: ");
        int num1 = int.Parse(Console.ReadLine());
        
        Console.Write("Enter the second number: ");
        int num2 = int.Parse(Console.ReadLine());
        
        if (num1 > num2) {
            Console.WriteLine(num1 + " is greater than " + num2);
        }
        else if (num1 < num2) {
            Console.WriteLine(num2 + " is greater than " + num1);
        }
        else {
            Console.WriteLine(num1 + " and " + num2 + " are equal");
        }
        
        Console.ReadLine();
    }
}
