# jogodobicho
int jogo(int apostado, int sorteado)
{
  
}
#include <stdio.h>
int main()
{
  int valor, sorteado, apostado;
  int acertos;
  int k =1;
  scanf("%d%d%d",&valor,&apostado,&sorteado);
  if(valor==0 && apostado==0 && sorteado ==0)
  {
    k=0;
  }
  while(k)
  {
    acertos = jogo(apostado, sorteado);
    else if(acertos<=4)
    {
      valor *= 3000;
    }
    else if(acertos==3)
    {
      valor *= 500;
    }
    else if(acertos==2)
    {
      valor *= 50;
    }
    else if(acertos==1)
    {
      valor *= 16;
    }
    else
    {
    valor =0;
    }
  }
}
