#include <stdio.h>

void main() {
  float lnth, wdth, perimeter, area;

  printf("Enter the length of the Rectangle:\n");
  scanf("%f", & lnth);
  
  printf("Enter the width of the Rectangle:\n");
  scanf("%f", & wdth);
  
  perimeter = 2 * (lnth + wdth);
  printf("Perimeter of the Rectangle: %0.4f\n", perimeter);

  area = lnth * wdth;
  printf("Area of the Rectangle: %0.4f\n", area);
}
