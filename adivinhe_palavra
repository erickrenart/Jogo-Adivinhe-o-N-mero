#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    srand(time(NULL));
    
    int numero_secreto = rand() % 100 + 1;
    int palpite;
    int tentativas = 0;
    
    printf("=== Jogo do Número Secreto ===\n");
    printf("Tente adivinhar o número secreto (1-100)!\n");
    printf("=================================\n");
    
    do {
        printf("Digite seu palpite: ");
        scanf("%d", &palpite);
        tentativas++;
        
        if (palpite < numero_secreto) {
            printf("É MAIOR que %d!\n", palpite);
        } else if (palpite > numero_secreto) {
            printf("É MENOR que %d!\n", palpite);
        }
        
        printf("=================================\n");
    } while (palpite != numero_secreto);
    
    printf("PARABÉNS!\n");
    printf("Você acertou em %d tentativas!\n", tentativas);
    printf("=================================\n");
    
    return 0;
}
