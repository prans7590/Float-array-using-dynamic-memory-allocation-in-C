# Float-array-using-dynamic-memory-allocation-in-C

#include <stdio.h>
#include <stdlib.h>

int main(int argc, char const *argv[])
{
    float *ptr;
    ptr = (float *) malloc(5*sizeof(float));     

   for (float i = 0  ; i < 5; i++){
       printf("enter the value of  %f elemetnt:  ", i );
       scanf("%f", &ptr[(int)i]);

   }
    for (float i = 0  ; i < 5; i++){
       printf("enter the value of  %f elemetnt is :%f  ", i , ptr[(int)i] );

    }
        return 0;
}
