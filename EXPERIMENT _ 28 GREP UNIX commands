#include<stdio.h>
#include<string.h>
int main()
{
char fn[30],pat[30],temp[200];
FILE *fp;
printf("Enter file name\n");
scanf("%s",fn);
printf("Enter pattern to be searched\n");
scanf("%s",pat);
fp=fopen(fn,"r");
while(!feof(fp))
{
fgets(temp,1000,fp);
if(strstr(temp,pat)!=NULL)
printf("%s",temp);
}
fclose(fp);
}
