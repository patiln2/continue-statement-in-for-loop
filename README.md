using System;
namespace CSharp_Shell
{
	public class program
	{
		public static void Main()
		{
			for(int x=1;x<=12;x++)
			{
				if(x==3)
				{
					continue;
				}
				Console.WriteLine(x);
			}
		}
	}
}
