Java
====

import java.util.Scanner;

class removeString
{

static int i, j;
static char[] aa;

static String input;



public static void main(String[] args)
	{
Scanner s = new Scanner(System.in);
System.out.println("Enter the string : ");
input = s.nextLine();

findS();
System.out.println(aa);
	}
public static void findS()
	{
	aa = input.toCharArray();
	
	for(i=0; i<aa.length;i++)
		{
		
		 if(aa[i] == 'a' && aa[i+1] =='c')
			{
			aa[i] = '\0';
			aa[i+1] = '\0';
			}
		if(aa[i] == 'b')
		{
		aa[i] = '\0';
		}
			
		}
	}
}
