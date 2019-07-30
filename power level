#include<stdio.h>
struct hero
{
    char name[20];
    int pwrlvl;
};
void main()
{
    struct hero h[10],t;
    int i,j,n;
    printf("enter no. of heroes:");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        scanf("%s %d",&h[i].name,&h[i].pwrlvl);
    }
    for(i=0;i<n;i++)
    {
        for(j=0;j<n-1;j++)
        {
            if(h[j].pwrlvl>h[j+1].pwrlvl)
            {
                t=h[j];
                h[j]=h[j+1];
                h[j+1]=t;
            }
        }
    }
    printf("****list****\n");
    for(j=0;j<n;j++)
    {
        printf("hero:%s\tpwrlvl:%d\n",h[j].name,h[j].pwrlvl);
    }
}
