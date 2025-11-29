
#include <stdio.h>
int main(){
char names[3][20];
int i;
printf("enter 3names:\n");
for(i=0; i<3; i++){
printf("Name %d:", i+1);
scanf("%s", names[i]);
}
printf("stored data: \n\n");
for(i=0;i<3;i++){
printf("Name %d:%s\n",i+1,names[i]);
return 0;
}
