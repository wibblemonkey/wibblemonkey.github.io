---
layout: post
title:  "Welcome to Metasyntactically Variable!"
date:   2018-11-05 15:45:31 +0000
---

So. After years of resisting the idea of making my internet footprint any larger
than it absolutely had to be, I finally find myself in the position of starting
a blog.

``` CSharp
/*
 * C# Program to Check whether the Entered Number is Even or Odd
 */
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace check1
{
    class Program
    {
        static void Main(string[] args)
        {
            int i;
            Console.Write("Enter a Number : ");
            i = int.Parse(Console.ReadLine());
            if (i % 2 == 0)
            {
                Console.Write("Entered Number is an Even Number");
                Console.Read();
            }
            else
            {
                Console.Write("Entered Number is an Odd Number");
                Console.Read();
            }
        }
    }
}
```