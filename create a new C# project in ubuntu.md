# create a new C# project in ubuntu
First create a new folder first

Then go to visual studio code and File -> Open Folder first

Then in visual studio code select tab Terminal located in the menu tab

Then in the terminal type

`dotnet new console`


`dotnet run`

Now replace 

`Console.WriteLine("Hello, World!");`

with

```
namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
} 
```
Now again replace the

`Console.WriteLine("Hello, World!");`

with

```
Console.WriteLine("What is your name?");
var name = Console.ReadLine();
var currentDate = DateTime.Now;
Console.WriteLine($"{Environment.NewLine}Hello, {name}, on {currentDate:d} at {currentDate:t}!");
Console.Write($"{Environment.NewLine}Press any key to exit...");
Console.ReadKey(true);
```

Now in the terminal type and press enter
`dotnet run`


