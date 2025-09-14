#include <stdio.h>
int main(){
  
  short int a;
  int b;
  long int c;
  
  scanf("%hd", &a);
  scanf("%d", &b);
  scanf("%ld", &c);
  
  printf("%hd\n", a);
  printf("%d\n", b);
  printf("%ld\n", c);
  
  return 0;
}
