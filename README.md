import java.io.*;
import java.util.*;
class Arraysum
{
public static void main(String args[])
  {
	Scanner input=new Scanner(System.in);
	int a=input.nextInt();
	int arr[]=new int[a];
	int sum=0;
	for(int i=0;i<a;i++)
	{
		arr[i]=input.nextInt();
		System.out.println();
	}
	for(int j=0;j<a;j++)
	{
		sum=sum+arr[j];
	}
	System.out.println(sum);
  }
} 
