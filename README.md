/*1 den 10 kadr olan sayilarin toplami*/
#include<stdio.h>

int main()
{
    int i;
    int toplam=0;

    for(i=0;i<=10;i++)
    {
        toplam+=i;

    }

    printf("Toplam:%d",toplam);

    return 0;

}
