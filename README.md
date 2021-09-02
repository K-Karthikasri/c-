#include<stdio.h>
int main()
{
int ch;
scanf("%c", &ch);
if((ch == 'a' || ch == 'e' || ch =='i' || ch == 'o' || ch == 'u') || (ch == 'A' || ch == 'E' || ch == 'O' || ch == 'U'))
{
printf("Vowel");
else
printf("Constanant");
return 0;
}
