# Algoritma
// Online C compiler to run C program online
#include <stdio.h>

int main() 
{
    int x,y;
    float z,pi;
    
    
    printf("x değerini giriniz:");
    scanf("%d",&x);
    
    printf("y değerini giriniz:");
    scanf("%d",&y);
    
    printf("z değerini giriniz:");
    scanf("%f",&z);
    
   // printf("pi değerini giriniz:");
    scanf("%f",&pi);
    
    x=20, y=50, z=10.5, pi=3.14 ;
    
    printf("x=%d y=%d z=%.2f pi=%.2f \n",x,y,z,pi);
    printf("++x = %d \n", ++x);
    printf("--y = %d \n", --y);
    printf("++z 0 %.2f \n", ++z);
    printf("--pi = %.2f \n", --pi);
    
    
    return 0;
}
