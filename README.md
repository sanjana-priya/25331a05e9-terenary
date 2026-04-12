
#include <stdio.h>
int main() {
printf("25331A05E9\n");
    int a, b, c, max;

    
    printf("Enter three numbers: ");
    
    
    scanf("%d %d %d", &a, &b, &c);

    
    max = (a > (b > c ? b : c)) ? a : (b > c ? b : c);

    
    printf("The maximum number is: %d\n", max);

    return 0;
}
