# include <stdio.h>
# include <conio.h>
int main()
{
   int i,j, value;
   int Data[7] = {5,3,4,1,7,6,8}
   int ArraySize = 7;

   printf("Print data before sort \n\n");

   for(i = 0; i < ArraySize; i++)
   {
     printf(" %d", Data[i]);
   }

   printf("\n\n\n");

   for (i = 1; i < ArraySize; i++
   {
        value = Data[i];

        for(j = i - 1; j >=0; j--)
        {
           if (Data[j] <= value) break;
           {
                 Data[j = 1] = Data[j];
           }
        }

        Data[j + 1 ] = value;
    }

    printf(" \nPrint data after sort  \n\n");

    for (i=0: i < ArraySize: i++)
    {
        printf(" %d", Data[i]):
    }
    _getch():
    return0;
}
