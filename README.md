# Day-of-the-week
Program that displays day of the week that corresponds to a number between 1-7 inclusive


#include <stdio.h>

int main()
{

	int week;
	
	printf("Please enter number corresponding to desired day of week: ");
	scanf("%d%*c", &week);
	
	if(week == 1)
	{
		printf("Monday");
	}
	else if(week == 2)
	{
		printf("Tuesday");
	}
	else if(week == 3)
	{
		printf("Wednesday");
	}
	else if(week == 4)
	{
		printf("Thursday");
	}	
	else if(week == 5)
	{
		printf("Friday");
	}	
	else if(week == 6)
	{
		printf("Saturday");
	}
	else if(week == 7)
	{
		printf("Sunday");
	}
	else if(week > 7)
	{
		printf("Please enter number between 1 and 7 inclusive\n");
	}	
	
	
	return(0);
}
