# C-code-4
Cross or X Pattern in C language

#include <stdio.h>

int main()
{
    int n;
    printf("Enter a number:");
    scanf("%d",&n);
    for(int i=1;i<=n;i++){
        for(int j=1;j<=n;j++){
            if(i==j||j==n-i+ 1){
                printf("* ");
            }
            else{
                printf("  ");
            }
        }
         printf("\n");
    }
    return 0;
}
