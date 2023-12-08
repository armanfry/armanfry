string Math = Console.ReadLine();
Console.WriteLine("Please Enter Number 1");
int Number1 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Please Enter Number 2");
int Number2 = Convert.ToInt32(Console.ReadLine());
switch (Math)
{
    case "+":
        Console.WriteLine(Number1 + Number2);
        break;
    case "-":
        Console.WriteLine(Number1 - Number2);
        break;
    case "*":
        Console.WriteLine(Number1 * Number2);
        break;
    case "/":
        Console.WriteLine(Number1 / Number2);
        break;
}
Console.ReadKey();