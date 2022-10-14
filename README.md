package javapractice;

import java.util.Scanner;

public class Assignment

{

	public static void main(String[] args)

	{

		int a[]= {1,2,3,5,6,7,8};

		System.out.println("Input Array : ");

		for(int i=0;i<a.length;i++)

		{

			System.out.print(a[i]+" ");

		}

		Scanner sc=new Scanner(System.in);

		System.out.println("\nEnter how many times you want to rotate array to left : ");

		int no=sc.nextInt();

		for(int i=0;i<no;i++)

		{

		    int first=a[0];
		    
		    if( i < 0 ){
		    	 System.out.println("Nin");

		   for(int j=0;j<a.length-1;j++)

		  {

			a[j]=a[j+1];

		  }

		  a[a.length-1]=first;

		}

		System.out.println("Output Array : ");

		for(int i1=0;i1<a.length;i1++)

		{

			System.out.print(a[i1]+" ");

		}

	}
	}
}

	
