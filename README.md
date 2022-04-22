# call-by-values-
using System;

class A
{
void Add(int i)
{
	i = i + 10;
}
public static void Main(String[] ar)
{
	int a = 10;

	A ob = new A();
	Console.WriteLine("Before calling the Add() method, the value in a is : " + a);
	ob.Add(a);
	Console.WriteLine("Afrer calling the Add() method, the value in a is : " + a);
}
}
