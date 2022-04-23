# function-overriding-
using System;
using System.Linq;
using System.Collections.Generic;
namespace CSharpShell
{
    Public class Program 
    {
    	Public virtual void showinfo()
    	{
    		Console.WriteLine(“base class method”);
    	}
    }
    Class b:Program
    {
    	Public override void showinfo()
    	{
    		Console.WriteLine(“derived class method”);
    	}
    
        Public static void Main()
        {
			B b1=new b();
			B1.showinfo();
			B1.showinfo();
        }
    }
}
