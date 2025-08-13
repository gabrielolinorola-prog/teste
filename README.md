# Teste - par ou impar 
Repositório de teste 

#include <stdio.h>

int main()
{
    int x;
    
    printf("Selecione um numero: ");
    scanf("%d", &x);
    
    if(x%2 == 0){
        printf("1");
    }else{
        printf("0");
    }

    return 0;
}
