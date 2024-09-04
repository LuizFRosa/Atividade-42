# Atividade-42

#include <stdio.h>
#include <conio.h>
#include <stdlib.h>
int main(void)
{
  int i;
  
  printf("Gerando 10 valores aleatorios:\n\n");
  
  for (i = 0; i < 10; i++)
  {
    printf("%d ", rand() % 100);
  }
  
  getch();
  return 0;
}
