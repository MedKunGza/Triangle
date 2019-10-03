#include <stdio.h>

int main()
{
    float x,y,z;
    printf("Input base = ");
    scanf("%f",&x);
    printf("Input height = ");
    scanf("%f",&y);
    z = x*y/2;
    printf("Area is = %.2f",z);
    return 0;
}
