# love-calculator-in-c-programming
hello this is a love calculator in c programming language u can use it is very help full download now
<h1>this is a Full Code</h1>
<h3>copyit or download it</h3>
.
#include<stdio.h>
#include<conio.h>
void main()
{

int i,l1;
long int s1,s2,t;
char name1[50],name2[50];
void title(),del();

title();

title();
printf("Please Enter your name\n");
scanf("%s",name1);

printf("Please Enter your partner's name\n" );
scanf("%s",name2);

for(i=0;i<8;i++)
{
 del();
}
title();

title();

printf("\n\nPress any key to view result\n\n");

l1=0;
for(i=0;i<50;i++)
{
 if (name1[i]!='\0')
 {
  l1++;
  continue;
}
break;
}
s1=0;

for(i=0;i<l1;i++)
{
 s1=s1+name1[i];
}
getch();
l1=0;

for(i=0;i<50;i++)
{
 if (name2[i]!='\0')
{
 l1++;
 continue;
}
 break;
}
s2=0;
for(i=0;i<l1;i++)
{
 s2=s2+name2[i];
}
t=s1+s2;
while(t>100)
{
    t=t/10;
}
title();
printf("the result is %ld%",t);
getch();
}
void title()
{
printf("!!!!!!!!! Love Calculator !!!!!!!!!\n");
}
void del()
{
printf("..");
}
