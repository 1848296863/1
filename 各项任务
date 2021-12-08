// 寻找素数
#include <stdio.h>
#include <stdlib.h> 
void sushu(int *date,int len)
{
       int i,j;
       for (i=0;i<len;i++){
             for (j=2;j<date[i];j++){
                   if (date[i]%j==0)  break;
                                               }
                   if (j==date[i]) printf("%d ",date[i]);
                                   }
}
int main ()
{
    int len,*a,i;
    scanf ("%d",&len);
    a=(int *)malloc(len*sizeof(int));
    for (i=0;i<len;i++){
         scanf("%d",&a[i]);
                                 }
     sushu(a,len);
}
