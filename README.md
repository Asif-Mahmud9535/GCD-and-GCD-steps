#include<stdio.h>
main()
{
    int i,n1,n2,r,ar[100];

    scanf("%d %d",&n1,&n2);

    for(i=0;n2!=0;i++)
    {
        r = n1%n2;
        ar[i]=r;
        n1 = n2;
        n2 = r;

    }
    printf("%d\n",n1);
    for(i=0;ar[i]!=0;i++)
    {
        printf("%d\t",ar[i]);
    }
}
