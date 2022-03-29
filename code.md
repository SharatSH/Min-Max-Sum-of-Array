using System;
using System.Linq;
					
public class Program
{
	public static void Main()
	{
		var arr = new int[]{1,3,5,7,9};
		var min = arr.Min();
		var max = arr.Max();
		var maxsum= arr.Sum()-min;
		var minsum= arr.Sum()-max;
		Console.WriteLine("MinSum:"+minsum);
		Console.WriteLine("MaxSum:"+maxsum);
	}
}
