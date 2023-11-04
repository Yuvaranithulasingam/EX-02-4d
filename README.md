# EX-02-4d    SUM OF EVEN DIGITS

## AIM:
To write a c program to find the sum of even digits using for loop.

## ALGORITHM:
1. Start the program.
2. Read a variable.
3. Using for loop print the sum of even digits.
4. Stop the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,i,s=0;
    scanf("%d",&a);
    for(i=1;i<=a;i++)
    {
       if(i%2==0)
       {
          s+= i;
          printf("%d ",i);
       }
    }
printf("\n%d ",s);
}
```

## OUTPUT:
![image](https://github.com/Yuvaranithulasingam/EX-02-4d/assets/121418522/6d77eee1-c0da-4c99-949a-1a3853c8cace)

## RESULT:
  Thus the program to find the sum of even digits using for loop has been executed
successfully.
