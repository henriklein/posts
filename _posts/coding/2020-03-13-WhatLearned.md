---
layout: post
title:  "C-Sharp"
date:   2020-03-08
categories: coding c-sharp
permalink: /:categories/:title
author: Henri Klein



---

## 01 Setup

## Need to know

C# is a backend a nd front-end developing language that is made to write code

1. Console 

   

```c#
1. console = class
2. console.writeline(); = Method (output, goes to a new line)
3. console.write(); = Method (same, stays in same line)
4. console.readkey(); = Method (wait for input)
5. console.readline(); = method (tases in a input)
  
   string content1 = Convert.ToString(Console.ReadLine());


```

Convert class

```C#
1. convert = class
2. convert.ToInt32(); (string -> Int)
3. convert.ToDouble(); (string -> double)
4. convert.ToFloat (sting -> float)
```



Math 

```C#
+
-
*
/
  
 
            double letsCallThatThingNum01;
            double letsCallThatThingNum02;

            Console.Write("Type in the dirst number u want to type in if u want to");
            letsCallThatThingNum01 = Convert.ToDouble(Console.ReadLine());
            Console.Write("Type in the second number u want ti type in if u want to");
            letsCallThatThingNum02 = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Division: " + letsCallThatThingNum01 / letsCallThatThingNum02);
            Console.WriteLine("Multiplication: " + letsCallThatThingNum01 * 					letsCallThatThingNum02);
            Console.WriteLine("Adding: " + (letsCallThatThingNum01 + letsCallThatThingNum02));
            Console.WriteLine("subsstration: " + (letsCallThatThingNum01 - letsCallThatThingNum02));
            Console.ReadKey();
```



Variable 

```c#
int num01; (,,,,-5,-3,0,2,6,...)
string Test ("Test?")
double
float (0.123892) 
long

```





## 02 Input-output

> I learned to give something out by typing a script (Hello World)
>
> I learned how to wait with the Console.ReadKey();
>
> ```c#
> using System;
> 
> namespace inputoutputB
> {
>     class MainClass
>     {
>         public static void Main(string[] args)
>         {
> 
> 
> 
>             
>             Console.WriteLine("Who am I? Someone that's afraid to let go, uh");
>             Console.ReadKey();
>             Console.WriteLine("You decide, if you're ever gonna, let me know (yeah)");
>             Console.ReadKey();
>             Console.WriteLine("Suicide, if you ever try to let go, uh");
>             Console.ReadKey();
>             Console.WriteLine("I'm sad and low, yeah");
>             Console.ReadKey();
>             Console.WriteLine("I'm sad and low, yeah");
>             Console.ReadKey();
>             Console.WriteLine("Who am I? Someone that's afraid to let go, uh");
>             Console.ReadKey();
>             Console.WriteLine("You decide, if you're ever gonna, let me know (yeah)");
>             Console.ReadKey();
>             Console.WriteLine("Suicide, if you ever try to let go, uh");
>             Console.ReadKey();
>             Console.WriteLine("I'm sad and low, yeah");
>             Console.ReadKey();
>             Console.WriteLine("I'm sad and low, yeah");
>             Console.ReadKey();
>         }
>     }
> }
> 
> ```

## 03 Variables and Calculations

> I learned how to asked for an user input, and then use simple math to calculate (+,-,*,/)
>
> ```c#
> using System;
> 
> namespace VariablesC
> {
>     class MainClass
>     {
>         public static void Main(string[] args)
>         {
>             Console.WriteLine("Trip Calculator");
> 
>             Double distance;
>             Double litres;
>             Double literPer100;
>             Double totalCost;
>             String vehicleType;
>             Console.WriteLine("Enter the total of distance you want to travel (in kilometers): ");
>             distance = Convert.ToDouble(Console.ReadLine());
>             Console.WriteLine("What car are you going to drive this trip: ");
>             vehicleType = Console.ReadLine();
>             Console.WriteLine("How much gas(Litres) does this car need to drive 100km: ");
>             litres = Convert.ToDouble(Console.ReadLine());
>             Console.WriteLine("how much does gas cost per litre: ");
>             literPer100 = Convert.ToDouble(Console.ReadLine());
> 
>             totalCost = (distance / 100) * litres * literPer100;
>             Console.WriteLine("This trip is going to cost $ " + totalCost + "  Since you are driving a: " + vehicleType + ".");
>             Console.ReadLine();
>         }
>     }
> }
> 
> ```
>
> 