# prgrm-6

Write a program to get a float value from the user and display it in the below-mentioned format

INPUT & OUTPUT FORMAT: 

Input consists of one float value. 

Output consists of one integer, its highest round off value and its lowest round off value.


#include<stdio.h>
#include<math.h>
int main()
{
    float x;
    scanf("%f",&x);
    printf("%.6f\n",x);
    printf("%.3f\n",x);
    printf("%.2f\n",x);
    printf("%.1f\n",x);
  return 0;
}
