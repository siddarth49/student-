#include <stdio.h>
int main()
{
  char Name[60];
    int Age; 
    float CGPA;
    char Grade;
scanf("%s %d %f %c", &Name, &Age, &CGPA, &Grade);

printf("Name: %s\n",Name);
printf("Age: %d\n", Age);
printf("CGPA: %.2f\n",floor(CGPA*100)/100);
printf("Grade: %c\n", Grade);
         
 return 0;
}
