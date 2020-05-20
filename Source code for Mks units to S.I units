#include<stdio.h>
main()
{         
            int choice;
		printf("\n Entre type of conversion you want  \n\n");
		printf("1.Kilometer to miles ");
		printf("\n 2.Inches to feet");
			printf("\n 3.Cm to Inches");
				printf("\n 4.Pound to kg");
					printf("\n 5.Inches to Meter");
					printf("\n 6.Kilometer to Meter");
					printf("\n 7.Fahrenhit to celsius");
					printf("\n 8.Celsius to fahrenhit");
					printf("\n 9.Millilitter to litter");
						scanf("\t\n\n%d",&choice );
						if(choice==1)
						{
							kilometer();
						}
						else if(choice==2)
						{
							inchfeet();
						}
							else if(choice==3)
						{
							cmtoinch();
						}
								else if(choice==4)
						{
							poundtokg();
						}
										else if(choice==5)
						{
							inchtometer();
						}
				else if(choice==6)
						{
							kilometertometer();
						}
						else if(choice==7)
						{
							fahrenhittocelsius();
						}
						else if(choice==8)
						{
								celsiustofahrenhit();
						}
					
						else {
						
							printf("Please entre a valid choice :");
					}
						
							return 0;
						}
					
kilometer()
{
	int km,ans;
	printf("\nEnter distance in kilometers");
	scanf("\n%d", &km);
	ans=km*0.62;
	printf("\n%d kilometer = %dmiles",km,ans);
	
}
inchfeet()
{
	int inch,ans;
	printf("\nEnter distance in inch");
	scanf("\n%d", &inch);
	ans=inch*0.083;
	printf("\n%d inches = %dfeets",inch,ans);
	
}
cmtoinch()
{
	int cm,ans;
	printf("\nEnter distance in cm");
	scanf("%d", &cm);
	ans=cm*0.39;
	printf("\n%d cm = %dfeet",cm,ans);
	
}
poundtokg()
{
	int pound,ans;
	printf("\nEnter weight in pound");
	scanf("\n%d", &pound);
	ans=pound*0.45;
	printf("\n%d pounds = %dkg",pound,ans);
	
}
inchtometer()
{
	int inch,ans;
	printf("\nEnter distance in inch");
	scanf("\n%d", &inch);
	ans=inch*0.02;
	printf("\n%dinches = %dmeter",inch,ans);
	
}
kilometertometer()
{
	int kilometer,ans;
	printf("\nEnter distance in kilometer");
	scanf("\n%d", &kilometer);
	ans=kilometer*1000;
	printf("\n%dkilometers  = %dmeters",kilometer,ans);	
}
	fahrenhittocelsius()
	{
		 float celsius, fahrenheit;
 
    printf("Please Enter the temperature in Fahrenheit: \n");
    scanf("%f", &fahrenheit);
 
    // Convert th temperature from fahrenheit to celsius formula
    celsius = (fahrenheit - 32) * 5 / 9;
    //celsius = 5 * (fahrenheit - 32) / 9;
    //celsius = (fahrenheit - 32) * 0.55556; 

    printf("\n %.2f Fahrenheit = %.2f Celsius", fahrenheit, celsius);
 
	}
	celsiustofahrenhit()
	{
		 float celsius, fahrenheit;

    /* Input temperature in celsius */
    printf("Enter temperature in Celsius: ");
    scanf("%f", &celsius);

    /* celsius to fahrenheit conversion formula */
    fahrenheit = (celsius * 9 / 5) + 32;

    printf("%.2f Celsius = %.2f Fahrenheit", celsius, fahrenheit);
	}

