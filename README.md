# Swaping-Number
#include <stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    for(int i=1;i<=10;i++){
        int m=i;
        if(i%2==0){
            m--;
        }
        else{
            m++;
        }
        printf("%d",m);
    }

    return 0;
}
