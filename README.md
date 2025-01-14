# Radius-to-Diameter-Circumference-Area
A C program that will ask the user for a radius of a circle (a floating-point number) and calculate and print the calculated diameter, circumference, and area 



    #include <stdio.h>

    int main (void)
    {
    float d = 0;
    float c = 0;
    float r = 0;
    float a = 0;
    
    printf("Please enter a radius of a circle: ");
    scanf("%f", &r);

    d = 2 * r;
    c = 2 * 3.14159 * r;
    a = 3.14159 * r * r;

    printf("The diameter of the circle is %.2f\n", d);
    printf("The circumference of the circle is %.2f\n", c);
    printf("The area of the circle is %.2f\n", a);
    return 0;

    }

**Sample Run:**

    Please enter a radius of a circle: 123.45
    The diameter of the circle is 246.90
    The circumference of the circle is 775.66
    The area of the circle is 47877.53
