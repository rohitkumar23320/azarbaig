#include<stdio.h>
void main()
{
 int a[10],i,n,*p=a;
 clrscr();
 printf("Enter the size of array: ");
 scanf("%d",&n);
 printf("Enter the Elements for array:\n");
 for(i=0;i<n;i++)
   scanf("%d",&p[i]);
 printf("----------------------------------\n");
 printf("values of the pointer is %d\n",*p);
 p=p+1;
 printf("After arithmetic addition Operator %d\n",*p);
 p++;
 printf("After Icrement Operation %d\n",*p);
 printf("\n----------------------------------------\n");
 printf("values of pointer %d\n",*p);
 p=p-1;
 printf("After Arithmetic Subtraction operation %d\n",*p);
 p--;
 printf("After Decrement operator %d\n",*p);
 getche();
}
