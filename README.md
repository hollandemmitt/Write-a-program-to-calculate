# Write-a-program-to-calculate
S = 1+ x + 2x2 + 3x3 + ... + n xn   Where x is a real number, n is an integer entered from the keyboard.
#include<stdio.h>
#include<conio.h>
#include<math.h>
main()
{    
    int n,i;
    float x,s=1;
    printf("Nhap x,n:");
    scanf("%f %d",&x,&n);
    for(i=1;i<=n;i++)
    {
        s=s+i*pow(x,i);        
    }
    printf(" Gia tri tinh duoc la:%0.2f ", s);
    getch();
}
