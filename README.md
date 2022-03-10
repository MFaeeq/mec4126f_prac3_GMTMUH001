# mec4126f_prac3_GMTMUH001
Prac 3 
#define STM32F051												   //COMPULSORY
#include "stm32f0xx.h"											   //COMPULSORY
#include "lcd_stm32f0.h"
#include "lcd_stm32f0.c"
#include <stdio.h>
#include <math.h>
// GLOBAL VARIABLES ----------------------------------------------------------|

typedef struct age_data
{
	int day;
	int month;
	int year;
	int age;

} my_age; 

// FUNCTION DECLARATIONS -----------------------------------------------------|

void main(void);                                                   //COMPULSORY

// MAIN FUNCTION -------------------------------------------------------------|

void main(void)
{
init_LCD();
age_data my_age={24, 8, 1999, 22};
char my_age[80];



	while(1)
	{
		for (int x=0; x<=p1.age;x++)
		{
			sprintf(my_age,"%d",x);
			lcd_putstring(faeeq);
			delay(800000);
			lcd_command(CLEAR);


		}


	}
}
