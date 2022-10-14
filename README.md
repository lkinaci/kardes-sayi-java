# kardes-sayi-java


package ders1;

import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
		Scanner input = new Scanner(System.in);
		Scanner input2 = new Scanner(System.in);
		
		int i,j,sayi1,sayi2;
		
		int	toplam1=0;
		int toplam2=0;
		
		System.out.println("Birinci sayiyi gir: ");
		sayi1 = input.nextInt();
		
		System.out.println("ikinci sayiyi gir: ");
		sayi2 = input2.nextInt();
		
		for(i=1;i<sayi1;i++)
		{
			if(sayi1%i==0)
			{
				toplam1+=i;
				
					
			}
		}
		
		for(j=1;j<sayi2;j++)
		{
			if(sayi2%j==0)
			{
				toplam2+=j;
				
					
			}
		}
		
		if(sayi1==toplam2 & sayi2==toplam1)
		{
			System.out.println(" bu sayılar kardes sayidir");
		}
		
		else
		{
			System.out.println("kardes sayi degiller");
		}

		
		
		
		
		

	}

}
