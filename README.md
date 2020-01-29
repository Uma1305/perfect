#include <stdio.h>
int main(){
   int n,i,sum=0,rem;
   printf("enter the num:");
   scanf("%d",&n);
   for(i=1;i<=n-1;i++)
   {
     rem=n%i;
     if(rem==0)
     {
         sum=sum+i;
     }
   }
     if(sum==n)
     {
         printf("perfect number");
     }
     else{
     printf("not perfect number");
     }
   
    return 0;
    
   
    
}
output:
enter the number:6
perfect number
