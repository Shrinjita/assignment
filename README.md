# assignment
srm homework
// Online C compiler to run C program online
#include <stdio.h>

int main()
{
    printf("*\n");
//int n=6;
    for(int i=1; i<=5; i++) {
        for(int j=6-i; j>=1; j--)
            printf(" ");
        for(int j =i*2-1; j>=1; j--)
            //for(int c =1;c<=j;c++)
            printf("*");
        printf("\n");
    }

    return 0;
}

