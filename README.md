# Array
#include <stdio.h>

int main() {
  int myNumbers[] = {25, 50, 75, 100};
  myNumbers[0] = 33;

  printf("%d", myNumbers[0]);
 
  return 0;
}
-------------------------------------------------------------------------------------
int myNumbers[] = {25, 50, 75, 100};
int i;

for (i = 0; i < 4; i++) {
  printf("%d\n", myNumbers[i]);
}
---------------------------------------------------------------------------------------
#include <stdio.h>

int main() {
  int myNumbers[] = {10, 25, 50, 75, 100};
  printf("%d", sizeof(myNumbers));
 
  return 0;
}
----------------------------------------------------------------------------------------
int main() {
    int mynumbers[]={25,30,40,50};
int length=sizeof(mynumbers)/ sizeof(mynumbers[0]);
int i;
for(i=0;i<length;i++){
printf("%d\n",mynumbers[i]);}
    return 0;
------------------------------------------------------------------------------------------
    int main() {
   int ages[]={12,15,17,18};
   int i;
    float sum,avg=0;
   for(i=0;i<4;i++)
        {sum=sum+ages[i];
        avg=sum/16;
        }
       printf("%f\n%f",sum,avg);
   
    return 0;
}
------------------------------------------------------------------------------------------

int main() {
   int ages[]={12,11,17,18};
   int i;
    int lowestAge=ages[0];
    for(i=0;i<4;i++){
        if(lowestAge >ages[i]){
            lowestAge=ages[i];
        }
    }
    printf("The lowest age in the array is: %d", lowestAge);
   return 0;
}
-------------------------------------------------------------------------------------------
int product_arr( int arr[]){
    int i;
    int result=1;
    for(i=0;i<3;i++)
    result=result*arr[i];
    return result;
}
int main(){
    int arr[]={20,30,10};
    printf("%d\n",product_arr(arr));
    return 0;}
-------------------------------------------------------------------------------------------

MULTIDIMENSIONAL ARRAY 

int main() {
  int matrix[2][3] = { {1, 4, 2}, {3, 6, 8} };
  printf("%d", matrix[0][2]);
 
  return 0;
}
-----------------------------------------------------------------------------------------
int main() {
  int matrix[2][3] = { {1, 4, 2}, {3, 6, 8} };

  int i, j;
  for (i = 0; i < 2; i++) {
    for (j = 0; j < 3; j++) {
      printf("%d\n", matrix[i][j]);
    }
  }
  
  return 0;
}
------------------------------------------------------------------------------------------
