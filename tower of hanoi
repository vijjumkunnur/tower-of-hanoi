#include<stdio.h>
void tower_of_hanoi(int n,char pegA,char pegB,char pegC)
{
  int elem;
  if(n==0)
  {
    printf("\n move disk 1 from peg %c to peg %c\n",pegA,pegB);
    }
    else
  {
    tower_of_hanoi(n-1,pegA,pegC,pegB);
    printf("\n move disk %d from peg %c to peg %c",n,pegA,pegB);
    tower_of_hanoi(n-1,pegC,pegB,pegA);
    }
  }
void main()
{
  int n,ch;
  while(1)
    {
      printf("1.solve tower of hanoi\n");
      printf("2.exit\n");
      printf("enter your choice\n");
      scanf("%d",&ch);
      switch(ch)
        {
          case 1:printf("enter number of disks\n");
          scanf("%d",&n);
          printf("the sequence involved in the tower of hanoi are:\n");
          tower_of_hanoi(n,'A','B','C');
          break;
          case 2:exit(0);
          default:printf("enter the valid choice\n");
          break;
          }
      }
 }
