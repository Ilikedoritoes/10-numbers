
#include <stdio.h>
#include <stdlib.h>
#include <iostream>
#define _CRT_SECURE_NO_WARNINGS

void main()
{
	float num1, num2, num3, num4, num5, num6, num7, num8, num9, num10;
	float max, min, avg;
	printf("Write 10 numbers.\n");
	scanf_s("%f %f %f %f %f %f %f %f %f %f", &num1, &num2, &num3, &num4, &num5, &num6, &num7, &num8, &num9, &num10);

	if ((num1 >= num2) && (num1 >= num3) && (num1 >= num4) && (num1 >= num5) && (num1 >= num6) && (num1 >= num7) && (num1 >= num8) && (num1 >= num9) && (num1 >= num10))
		max = num1;
	if ((num2 >= num1) && (num2 >= num3) && (num2 >= num4) && (num2 >= num5) && (num1 >= num6) && (num2 >= num7) && (num2 >= num8) && (num2 >= num9) && (num2 >= num10))
		max = num2;
	if ((num3 >= num1) && (num3 >= num2) && (num3 >= num4) && (num3 >= num5) && (num3 >= num6) && (num3 >= num7) && (num3 >= num8) && (num3 >= num9) && (num3 >= num10))
		max = num3;
	if ((num4 >= num1) && (num4 >= num2) && (num4 >= num3) && (num4 >= num5) && (num4 >= num6) && (num4 >= num7) && (num4 >= num8) && (num4 >= num9) && (num4 >= num10))
		max = num4;
	if ((num5 >= num1) && (num5 >= num2) && (num5 >= num4) && (num5 >= num3) && (num5 >= num6) && (num5 >= num7) && (num5 >= num8) && (num5 >= num9) && (num5 >= num10))
		max = num5;
	if ((num6 >= num1) && (num6 >= num2) && (num6 >= num4) && (num6 >= num5) && (num6 >= num3) && (num6 >= num7) && (num6 >= num8) && (num6 >= num9) && (num6 >= num10))
		max = num6;
	if ((num7 >= num1) && (num7 >= num2) && (num7 >= num4) && (num7 >= num5) && (num7 >= num6) && (num7 >= num3) && (num7 >= num8) && (num7 >= num9) && (num7 >= num10))
		max = num7;
	if ((num8 >= num1) && (num8 >= num2) && (num8 >= num4) && (num8 >= num5) && (num8 >= num6) && (num8 >= num7) && (num8 >= num3) && (num8 >= num9) && (num8 >= num10))
		max = num8;
	if ((num9 >= num1) && (num9 >= num2) && (num9 >= num4) && (num9 >= num5) && (num9 >= num6) && (num9 >= num7) && (num9 >= num8) && (num9 >= num3) && (num9 >= num10))
		max = num9;
    if ((num6 >= num1) && (num6 >= num2) && (num6 >= num4) && (num10 >= num5) && (num10 >= num6) && (num10 >= num7) && (num10 >= num8) && (num10 >= num9) && (num10 >= num3))
		max = num10;

	/// 
	/// 
	/// 

	if ((num1 <= num2) && (num1 <= num3) && (num1 <= num4) && (num1 <= num5) && (num1 <= num6) && (num1 <= num7) && (num1 <= num8) && (num1 <= num9) && (num1 <= num10))
		min = num1;
	if ((num2 <= num1) && (num2 <= num3) && (num2 <= num4) && (num2 <= num5) && (num1 <= num6) && (num2 <= num7) && (num2 <= num8) && (num2 <= num9) && (num2 <= num10))
		min = num2;
	if ((num3 <= num1) && (num3 <= num2) && (num3 <= num4) && (num3 <= num5) && (num3 <= num6) && (num3 <= num7) && (num3 <= num8) && (num3 <= num9) && (num3 <= num10))
		min = num3;
	if ((num4 <= num1) && (num4 <= num2) && (num4 <= num3) && (num4 <= num5) && (num4 <= num6) && (num4 <= num7) && (num4 <= num8) && (num4 <= num9) && (num4 <= num10))
		min = num4;
	if ((num5 <= num1) && (num5 <= num2) && (num5 <= num4) && (num5 <= num3) && (num5 <= num6) && (num5 <= num7) && (num5 <= num8) && (num5 <= num9) && (num5 <= num10))
		min = num5;
	if ((num6 <= num1) && (num6 <= num2) && (num6 <= num4) && (num6 <= num5) && (num6 <= num3) && (num6 <= num7) && (num6 <= num8) && (num6 <= num9) && (num6 <= num10))
		min = num6;
	if ((num7 <= num1) && (num7 <= num2) && (num7 <= num4) && (num7 <= num5) && (num7 <= num6) && (num7 <= num3) && (num7 <= num8) && (num7 <= num9) && (num7 <= num10))
		min = num7;
	if ((num8 <= num1) && (num8 <= num2) && (num8 <= num4) && (num8 <= num5) && (num8 <= num6) && (num8 <= num7) && (num8 <= num3) && (num8 <= num9) && (num8 <= num10))
		min = num8;
	if ((num9 <= num1) && (num9 <= num2) && (num9 <= num4) && (num9 <= num5) && (num9 <= num6) && (num9 <= num7) && (num9 <= num8) && (num9 <= num3) && (num9 <= num10))
		min = num9;
	if ((num6 <= num1) && (num6 <= num2) && (num6 <= num4) && (num10 <= num5) && (num10 <= num6) && (num10 <= num7) && (num10 <= num8) && (num10 <= num9) && (num10 <= num3))
		min = num10;



	    printf("the maximum number is %f\n", max);
	    printf("the minimum number is %f\n", min);
	    avg = ((num1 + num2 + num3 + num4 + num5 + num6 + num7 + num8 + num9 + num10) / 10);
	    printf("the average of the numbers is %f\n", avg);
		printf("%f %f %f %f %f %f %f %f %f %f\n", num10, num9, num8, num8, num7, num6, num5, num4, num3, num2, num1);
	
	    system("pause");

}
