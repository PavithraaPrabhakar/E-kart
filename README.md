# E-kart
package com.gqt.ekartapplication.project;
import java.util.Scanner;
/**
 * Different Methods for performing different operations 
 *
 */
public class EkartApplication {
	public static int key;
	public static int key1;
	public static String key2;

	public static void Exit()
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("Do you wish to quit??");
		String s1=new String();
		s1=sc.next();
		if(s1.equals("no")==true)
		{
			main(null);
		}
		else
		{
			System.out.println("Thank you!!");
			System.exit(0);
		}

	}
	public static void HomeDecors()
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("\t\t\tWelcome To Home Decors\t\t\t");
		System.out.println("\t\t\t**********************\t\t\t");
		System.out.println();
		System.out.println("Please Select the option of your choice\n"
				+ "1.Furniturs\n"
				+ "2.Blankets\n"
				+ "3.Carpets\n"
				+ "4.Kitchen Decors\n");
		key1=sc.nextInt();
		switch(key1)
		{
		case 1:
		{
			System.out.println("Welcome to Furniture Store\n");
			System.out.println("***************************");
			System.out.println();
			System.out.println("Choose the option of your choice\n"
					+ "1.Sofa Set\n"
					+ "2.Tables\n");
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Sofa Set stores");
				System.out.println("\t\t\t...........................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost-50,000\t"
						+ "Wood type-Teak\t"
						+ "Seatings-5\t");
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("Iteam\t\t\tPrice");
					System.out.println("1.Sofa\t\t\t50000");
					System.out.println("2.Sofa\t\t\t50000");
					System.out.println(".............................");
					System.out.println("Total\t\t\t100000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to Tables stores");
				System.out.println("\t\t\t..........................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost-50,000 \t "
						+ "Wood type-Sandal \t"
						+ "Seatings-5 \t");
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("Iteam\t\t\tPrice");
					System.out.println("1.Table\t\t\t50000");
					System.out.println("2.Desk \t\t\t50000");
					System.out.println(".............................");
					System.out.println("Total\t\t\t100000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}break;
			}
			}
			break;
		}
		case 2:
		{
			System.out.println("Welcome to Blanket Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Wollen Blankets\n"
					+ "2.Normal Blankets");
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Woolen Blanket stores");
				System.out.println("\t\t\t..................................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tType\t\tColor");
				System.out.println("4000\t\tKlotthe\t\tBaby pink");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Blanket\t\t\t4000");
					System.out.println("2.Blanket\t\t\t4000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t8000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to Normal Blankets stores");
				System.out.println("\t\t\t..................................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\\t\\tType\\t\\tColor\t\tSize");
				System.out.println("2000\t\tKlotthe\t\tBaby pink\t\tSmall");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Blanket\t\t\t2000");
					System.out.println("2.Blanket\t\t\t2000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t4000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}
				break;
			}
			}
			break;
		}
		case 3:
		{
			System.out.println("Welcome to Carpet Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Door Carpets\n"
					+ "2.Hall Carpets");	
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Door Carpets stores");
				System.out.println("\t\t\t...............................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tType\t\tColor\t\t\tsize");
				System.out.println("1000\t\tSifa\t\tMulticolour\tLarge");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to Normal Blankets stores");
				System.out.println(".........................................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\\t\\tType\\t\\tColor\t\tSize");
				System.out.println("1500\t\tShanno\t\tMulticolor\t\tXLarge");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Carpett\t\t\t1500");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t1500");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");;
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}


				break;
			}
			}

			break;
		}
		case 4:
		{
			System.out.println("Welcome to Kitchen decor Store\n");
			System.out.println("********************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Ceramic Cups\n"
					+ "2.Vessels\n");
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t \t Welcome to Ceramic stores");
				System.out.println("\t\t\t..........................");
				System.out.println();
				System.out.println("Different Types of Ceramic cups available\n"
						+ "Buy 3 And Get 1 Free");
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tType\t\tCompany");
				System.out.println("500\t\tCeramic\t\tMilton");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Cups  \t\t\t500");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t500");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to Vessels stores");
				System.out.println("\t\t\t..........................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tType\t\tQuantity\t\tSize");
				System.out.println("2000\t\tSteel\t\t4pieces\t\tSmall");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Vessels\t\t\t2000");
					System.out.println("2.Vessels\t\t\t2000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t4000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}
				break;
			}
			}
			break;
		}
		}
	}
	public static void Electronics()
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("Welcome To Electronics");
		System.out.println("***********************");
		System.out.println();
		System.out.println("Please Select the option of your choice\n"
				+ "1.MObiles\n"
				+ "2.Headphones\n"
				+ "3.Laptops\n"
				+ "4.Tabs\n");
		key1=sc.nextInt();
		switch(key1)
		{
		case 1:
		{
			System.out.println("Welcome to Mobile Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.iPhone\n"
					+ "2.One plus\n");
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to iPhone stores");
				System.out.println("\t\t\t.........................");
				System.out.println();
				System.out.println("Different iPhone Brands are available\n"
						+ "1.iPhone-14ProMax\n"
						+ "2.iPhone-14");
				key1=sc.nextInt();
				System.out.println("**Features**");
				System.out.println("Cost\t\tRAM\t\tColor");
				System.out.println("1,30,000\t\t16gb\t\tBlack");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.iPhone\t\t\t130000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t130000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to OnePlus stores");
				System.out.println("\t\t\t..........................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\\t\\tRAM\\t\\tColor\t\tSpace");
				System.out.println("40,000\t\t16gb\t\tBlue\t\t128gb");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Oneplus8\t\t40,000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t40,000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}
				break;
			}
			}

			break;
		}
		case 2:
		{
			System.out.println("Welcome to Headphone Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Boat\n"
					+ "2.Oneplus");
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Boat Rokerz stores");
				System.out.println("\t\t\t..............................");
				System.out.println();
				System.out.println("***Buy any product and get offer upto 25%***");
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tType\t\tColor");
				System.out.println("1,300\t\tWireless\tBlack");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Wireless\t\t\t1300");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t1300");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to OnePlus stores");
				System.out.println("\t\t\t..........................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tType\t\tColor");
				System.out.println("2,500\t\tEarBuds\t\tBlue");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Earbuds\t\t\t2500");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t2500");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}
				break;
			}
			}
			break;
		}
		case 3:
		{
			System.out.println("Welcome to Laptop Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Mac Book\n"
					+ "2.Dell");	
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Mac Book stores");
				System.out.println("\t\t\t............................");
				System.out.println();
				System.out.println("**Features**");
				System.out.println("Cost\t\tRAM\t\tColor");
				System.out.println("84,000\t\t16gb\t\tBlack");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.MACbook\t\t84,000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t84000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to Dell stores");
				System.out.println("\t\t\t........................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tRAM\t\tColor\t\tSpace");
				System.out.println("40,000\t\t16gb\t\tSilver\t\t128gb");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Dell\t\t\t40,000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t40000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}
				break;
			}
			}
			break;
		}
		case 4:
		{
			System.out.println("Welcome to Tab Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Apple\n");
			key1=sc.nextInt();
			System.out.println("**Specifications**");
			System.out.println("Cost\\t\\tRAM\\t\\tColor\t\tSpace");
			System.out.println("48,000\t\t16gb\t\tSilver\t\t128gb");		 
			System.out.println("Do you wish to shop");
			boolean b = sc.nextBoolean();
			if(b==true)
			{
				System.out.println("Thank you for shopping");
			}

			else {
				System.out.println("Thank you for visiting our stores");
				Exit();
			}

			break;
		}
		}
	}
	public static void Fashions()
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("\t\t\tWelcome To Fashions\t\t\t");
		System.out.println("\t\t\t********************");
		System.out.println();
		System.out.println("Please Select the option of your choice\n"
				+ "1.Men\n"
				+ "2.Women\n"
				+ "3.Children\n");
		key1=sc.nextInt();
		switch(key1)
		{
		case 1:
		{
			System.out.println("Welcome to Mens Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Shirts\n"
					+ "2.Ethnic Wears\n");
			key1=sc.nextInt();switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Shirts section");
				System.out.println("\t\t\t...........................");
				System.out.println();
				System.out.println("Buy 2 shirts and get 1 free ");
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tFabric\t\tColor");
				System.out.println("1999\t\tSilk\t\tMultiColors");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Shirt\t\t\t1999");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t1999");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to Ethnic Wear section");
				System.out.println("\t\t\t................................");
				System.out.println();
				System.out.println("*Different ethnic wears at same cost*\n"
						+ "**Buy any material at flat 50% off**");
				System.out.println("**Specifications**");
				System.out.println("Cost\\t\\tFabric\\t\\tColor\t\tSize");
				System.out.println("2,000\t\tCotton\t\tMulticolors\t\tDiff sizes available");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Silk  \t\t\t2000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t2000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}
				break;
			}
			}
			System.out.println("Thankyou for Shopping");
			break;
		}
		case 2:
		{
			System.out.println("Welcome to Women Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Western Wear\n"
					+ "2.Kurtis");
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Western wear section");
				System.out.println("\t\t\t................................");
				System.out.println();
				System.out.println("Different Categories\n"
						+ "1.Frocks\n"
						+ "2.Skirts\n"
						+ "Buy any at same cost ");
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tFabric\t\tColor");
				System.out.println("3,000\t\tDesigner\t\tDiff colors");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Frocks\t\t\t3000");
					System.out.println("2.Skirts\t\t\t3000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t6000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}
				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to Kurtis section");
				System.out.println("\t\t\t.........................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\\t\\tFabric\\t\\tColor\t\tSize");
				System.out.println("2,000\t\tDiff fab\t\tMulti colors\t\tDiff sizes available");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Kurti\t\t\t2000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t2000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}
				break;
			}
			}
			break;
		}
		case 3:
		{
			System.out.println("Welcome to Children Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Frocks\n"
					+ "2.Trousers");	
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Frocks section");
				System.out.println("\t\t\t...........................");
				System.out.println();

				System.out.println("**Specifications**");
				System.out.println("Cost\t\tFabric\t\tColor");
				System.out.println("3,000\t\tDesigner\t\tDiff colors");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Frocks\t\t\t3000");

					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t3000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}
				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}
			case 2:
			{
				System.out.println("\t\t\t Welcome to Trousers section");
				System.out.println("\t\t\t.............................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\\t\\tFabric\\t\\tColor\t\tSize");
				System.out.println("2,000\t\tDiff fab\t\tMulti colors\t\tDiff sizes available");		 
				System.out.println("Do you wish to shop");
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Trousers\t\t\t2000");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t2000");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}


				break;
			}
			}
			break;	
		}
		}
	}
	public static void InstaMart()
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("Welcome To Instamart");
		System.out.println("***************************");
		System.out.println();
		System.out.println("Please Select the option of your choice\n"
				+ "1.Fruits and Veggies\n"
				+ "2.Juices\n"
				+ "3.Cerals\n"
				+ "4.Provisions\n");
		key1=sc.nextInt();
		switch(key1)
		{
		case 1:
		{
			System.out.println("Welcome to Fruits and Veggies Store\n");
			System.out.println("************************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Fruits\n"
					+ "2.Veggies\n");
			key1=sc.nextInt();
			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\t Welcome to Fruits store");
				System.out.println("\t\t\t........................");
				System.out.println();
				System.out.println("Different Fruits available\n"
						+ "1.Apple\n"
						+ "2.Orange\n");
				key1=sc.nextInt();
				switch(key1)
				{
				case 1:
				{
					System.out.println("\t\t\tWelcome to Apple Section");
					System.out.println("\t\t\t.........................");
					System.out.println();
					System.out.println("**Specifications**");
					System.out.println("Cost\t\tQuantity\t\t");
					System.out.println("100\t\tPer Kg\t\t");		
					System.out.println("Do you wish to purchase");
					//String key2=sc.next();			
					boolean b = sc.nextBoolean();
					if(b==true)
					{
						System.out.println("Thank you for shopping");
						System.out.println("*Here's your Bill*");
						System.out.println("\tCASH RECEIPT\t\t\t");
						System.out.println("\t.............\t\t\t");
						System.out.println("\tIteam\t\t\tPrice");
						System.out.println("1.Applejuice\t\t\t100");
						System.out.println(".............................");
						System.out.println("\tTotal\t\t\t\t100");
						System.out.println("......Thank You.....\n"
								+ "VISIT AGAIN!!!");
					}

					else {
						System.out.println("Thank you for visiting our stores");
						Exit();
					}
					break;
				}
				case 2:
				{
					System.out.println("\t\t\tWelcome to Orange Section");
					System.out.println("\t\t\t..........................");
					System.out.println("**Specifications**");
					System.out.println("Cost\t\tQuantity\t\t");
					System.out.println("130\t\tPer Kg\t\t");		
					System.out.println("Do you wish to purchase");
					//String key2=sc.next();			
					boolean b = sc.nextBoolean();
					if(b==true)
					{
						System.out.println("Thank you for shopping");
						System.out.println("*Here's your Bill*");
						System.out.println("\tCASH RECEIPT\t\t\t");
						System.out.println("\t.............\t\t\t");
						System.out.println("\tIteam\t\t\tPrice");
						System.out.println("1.Orangejuice\t\t100");
						System.out.println(".............................");
						System.out.println("\tTotal\t\t\t\t130");
						System.out.println("......Thank You.....\n"
								+ "VISIT AGAIN!!!");
					}

					else {
						System.out.println("Thank you for visiting our stores");
						Exit();
					}

					break;
				}	
				}
				break;
			}

			case 2:
			{
				System.out.println("\t\t\t Welcome to Vegetable section");
				System.out.println("\t\t\t..............................");
				System.out.println();
				System.out.println("Different Fruits available\n"
						+ "1.Cucumber\n"
						+ "2.Tomato\n");
				key1=sc.nextInt();
				switch(key1)
				{
				case 1:
				{
					System.out.println("\t\t\tWelcome to Cucumber Section");
					System.out.println("\t\t\t...........................");
					System.out.println();
					System.out.println("**Specifications**");
					System.out.println("Cost\t\tQuantity\t\t");
					System.out.println("10\t\tPer piece\t\t");		
					System.out.println("Do you wish to purchase");
					//String key2=sc.next();			
					boolean b = sc.nextBoolean();
					if(b==true)
					{
						System.out.println("Thank you for shopping");
						System.out.println("*Here's your Bill*");
						System.out.println("\tCASH RECEIPT\t\t\t");
						System.out.println("\t.............\t\t\t");
						System.out.println("\tIteam\t\t\tPrice");
						System.out.println("1.Cucumber\t\t100");
						System.out.println(".............................");
						System.out.println("\tTotal\t\t\t100");
						System.out.println("......Thank You.....\n"
								+ "VISIT AGAIN!!!");
					}

					else {
						System.out.println("Thank you for visiting our stores");
						Exit();
					}
					break;
				}
				case 2:
				{
					System.out.println("\t\t\tWelcome to Tomato Section");
					System.out.println("\t\t\t.........................");
					System.out.println();
					System.out.println("**Specifications**");
					System.out.println("Cost\t\tQuantity\t\t");
					System.out.println("130\t\tPer Kg\t\t");		
					System.out.println("Do you wish to purchase");
					//String key2=sc.next();			
					boolean b = sc.nextBoolean();
					if(b==true)
					{
						System.out.println("Thank you for shopping");
						System.out.println("*Here's your Bill*");
						System.out.println("\tCASH RECEIPT\t\t\t");
						System.out.println("\t.............\t\t\t");
						System.out.println("\tIteam\t\t\tPrice");
						System.out.println("1.Tomato\t\t\t130");
						System.out.println(".............................");
						System.out.println("\tTotal\t\t\t\t130");
						System.out.println("......Thank You.....\n"
								+ "VISIT AGAIN!!!");
					}

					else {
						System.out.println("Thank you for visiting our stores");
						Exit();
					}

					break;
				}	
				}
				break;
			}
			}
			break;
		}

		case 2:
		{
			System.out.println("Welcome to Juices Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.ButterScoch\n"
					+ "2.Pineapple flavours");
			key1=sc.nextInt();

			switch(key1)
			{
			case 1:
			{
				System.out.println("\t\t\tWelcome to ButterScoch Store");
				System.out.println("\t\t\t...........................");
				System.out.println();
				System.out.println("**Specifications**");
				System.out.println("Cost\t\tType\t\t");
				System.out.println("50\t\tMix Fruit With icecream\t\t");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Butterscoch\t\t50");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t50");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}
				break;
			}
			case 2:
			{
				System.out.println("\t\t\tWelcome to Flavours Section");
				System.out.println("\t\t\t...........................");
				System.out.println("**Specifications**");
				System.out.println();
				System.out.println("**PineApple Flavours**");
				System.out.println("Cost\t Type\t\t");
				System.out.println("130\t\tPineapple\t\t");		
				System.out.println("Do you wish to purchase");
				//String key2=sc.next();			
				boolean b = sc.nextBoolean();
				if(b==true)
				{
					System.out.println("Thank you for shopping");
					System.out.println("*Here's your Bill*");
					System.out.println("\tCASH RECEIPT\t\t\t");
					System.out.println("\t.............\t\t\t");
					System.out.println("\tIteam\t\t\tPrice");
					System.out.println("1.Pineapple\t\t\t130");
					System.out.println(".............................");
					System.out.println("\tTotal\t\t\t\t130");
					System.out.println("......Thank You.....\n"
							+ "VISIT AGAIN!!!");
				}

				else {
					System.out.println("Thank you for visiting our stores");
					Exit();
				}

				break;
			}	
			}
			break;
		}



		case 3:
		{
			System.out.println("Welcome to Cereals Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Corns\n"
					+ "2.Greengram");	
			key1=sc.nextInt();
			Exit();
			System.out.println("Thankyou for Shopping");
			break;
		}
		case 4:
		{
			System.out.println("Welcome to Provision Store\n");
			System.out.println("***************************");
			System.out.println("Choose the option of your choice\n"
					+ "1.Oil\n");
			key1=sc.nextInt();
			Exit();
			System.out.println("Thankyou for Shopping");
			break;
		}
		}
	}

	public static void Sports()
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("Welcome To Sports");
		System.out.println("***************************");
		System.out.println();
		System.out.println("Please Select the option of your choice\n"
				+ "1.Sports wears\n"
				+ "2.Sports equipments\n"
				+ "3.Sports shoes\n");
		key1=sc.nextInt();
		switch(key1)
		{
		case 1:
		{
			System.out.println("Welcome to Sports Wears");
			System.out.println("***************************");
			System.out.println();
			System.out.println("1.Tracks");
			key1=sc.nextInt();
			System.out.println("**Specifications**");
			System.out.println("Cost\\t\\tFabric\\t\\tColor\t\tSize");
			System.out.println("2,000\t\tJersi\t\tMulti colors\t\tDiff sizes available");		 
			System.out.println("Do you wish to shop");
			boolean b = sc.nextBoolean();
			if(b==true)
			{
				System.out.println("Thank you for shopping");
				System.out.println("*Here's your Bill*");
				System.out.println("\tCASH RECEIPT\t\t\t");
				System.out.println("\t.............\t\t\t");
				System.out.println("\tIteam\t\t\tPrice");
				System.out.println("1.Tracks\t\t\t2000");
				System.out.println(".............................");
				System.out.println("\tTotal\t\t\t\t2000");
				System.out.println("......Thank You.....\n"
						+ "VISIT AGAIN!!!");
			}

			else {
				System.out.println("Thank you for visiting our stores");
				Exit();
			}
			break;
		}
		case 2:
		{
			System.out.println("Welcome to Sports equipments");
			System.out.println("***************************");
			System.out.println();
			System.out.println("1.Bats");
			key1=sc.nextInt();
			System.out.println("**Specifications**");
			System.out.println("Cost\t\tColor");
			System.out.println("2,000\t\tMulti colors");		 
			System.out.println("Do you wish to shop");
			boolean b = sc.nextBoolean();
			if(b==true)
			{
				System.out.println("Thank you for shopping");
				System.out.println("*Here's your Bill*");
				System.out.println("\tCASH RECEIPT\t\t\t");
				System.out.println("\t.............\t\t\t");
				System.out.println("\tIteam\t\t\tPrice");
				System.out.println("1.Bats \t\t\t2000");
				System.out.println(".............................");
				System.out.println("\tTotal\t\t\t2000");
				System.out.println("......Thank You.....\n"
						+ "VISIT AGAIN!!!");
			}

			else {
				System.out.println("Thank you for visiting our stores");
				Exit();
			}
			break;
		}
		case 3:
		{
			System.out.println("Welcome to Sports Shoes");
			System.out.println("***************************");
			System.out.println();
			System.out.println("1.Nike");
			key1=sc.nextInt();
			System.out.println("**Specifications**");
			System.out.println("Cost\t\tColor\t\tSize");
			System.out.println("2,000\t\tMulti colors\t\tDiff Sizes available");		 
			System.out.println("Do you wish to shop");
			boolean b = sc.nextBoolean();
			if(b==true)
			{System.out.println("Thank you for shopping");
			System.out.println("*Here's your Bill*");
			System.out.println("\tCASH RECEIPT\t\t\t");
			System.out.println("\t.............\t\t\t");
			System.out.println("\tIteam\t\t\tPrice");
			System.out.println("1.Shoes\t\t\t2000");
			System.out.println(".............................");
			System.out.println("\tTotal\t\t\t2000");
			System.out.println("......Thank You.....\n"
					+ "VISIT AGAIN!!!");
			}

			else {
				System.out.println("Thank you for visiting our stores");
				Exit();
			}
			break;
		}

		}
	}

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
		System.out.println("\t\t\t\t\tWelcome to Ekart Application\t\t\t\t\t");
		System.out.println("\t\t\t\t\t****************************\t\t\t\t\t");
		System.out.println();
		System.out.println("Choose the option you wish to shop \n"
				+ "1.Home Decors\n"
				+ "2.Electronics\n"
				+ "3.Fashion\n"
				+ "4.Instamart\n"
				+ "5.Sports\n"
				+ "6.Exit\n");
		key=sc.nextInt();
		switch(key)
		{
		case 1:
		{
			HomeDecors();
			break;
		}
		case 2:
		{
			Electronics();
			break;
		}
		case 3:
		{
			Fashions();
			break;

		}
		case 4:
		{
			InstaMart();
			break;
		}
		case 5:
		{
			Sports();
			break;
		}
		case 6:
		{
			Exit();
			break;
		}
		}
	}

}
