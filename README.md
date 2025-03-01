# C-Program-Geometry

PROBLEM 13 = 

#include<stdio.h>
int main()
{
    int b,h,area;
    printf("Enter Base of a Triangle - ");
    scanf("%d",&b);
    printf("Enter height of a Triangle - ");
    scanf("%d",&h);
    area = 0.5*b*h;
    printf("area - 0.5 * %d *%d = %d",b,h,area);
    return 0;
}

PROBLEM 14 = 

#include<stdio.h>
int main()
{
    int r,area;
    printf("Enter radius of a circle - ");
    scanf("%d",&r);
    area = 3.1416 * r*r;
    printf("area = 3.1416* %d = %d",r,area);
    return 0 ;
}
