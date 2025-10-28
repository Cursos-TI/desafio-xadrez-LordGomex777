#include <stdio.h>

int main(){

    //Variaveis das peças:
    int torre = 1, bispo = 1, rainha = 1;

    //Movimmento da Torre com while:
        printf("Movimento da Torre:\n");
    while (torre <= 6 ){
        printf("Cima\n");
        torre ++;
    }

    //Movimento do Bispo com do-while:
        printf("Movimento do Bispo:\n");
    do
    {
        printf("Cima direita\n");
        bispo ++;
    } while (bispo <= 5);

    //Movimento Rainha com for:
    printf("Movimento da Rainha:\n");
    for (rainha = 1; rainha <= 8; rainha++)
    {
        printf("Esquerda\n");
    }
        
return 0;
}
