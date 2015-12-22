#include <stdio.h>
int main()
{
  int n, n1, rem, num=0;
  printf("Enter a positive  integer: ");
  scanf("%d", &n);
  n1=n;
  while(n1!=0)
  {
      rem=n1%10;
      num+=rem*rem*rem;
      n1/=10;
  }
  if(num==n)
    printf("%d is an Armstrong number.",n);
  else
    printf("%d is not an Armstrong number.",n);
}
