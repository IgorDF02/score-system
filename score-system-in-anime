#include <stdio.h>
#include <stdlib.h>
#include <locale.h>
#include <stdbool.h>
#include <string.h>

int main()
{   char ind[10], op[10], rec[10], ruim[10], exist[10];
    
    printf("\tVamos saber a nota do anime! (responda com 'sim' ou 'não')");
    
    printf("\nIndico esse anime para alguém? ");
    scanf("%s", ind);
    
    if(strcmp(ind, "sim") == 0){
        printf("\nÉ uma obra-prima? ");
        scanf("%s", op);
        
        if(strcmp (op, "sim") == 0){
            printf("nota do anime: 10");
        }else{
            printf("nota do anime: 9");   
        }
    
    }else{
        printf("\nDesrecomendo? ");
        scanf("%s", rec);
        
        if(strcmp(rec, "não") == 0){
            printf("nota do anime: 7");
        }else{
            printf("\nÉ ruim? ");
            scanf("%s", ruim);
                
                if (strcmp(ruim, "não") == 0){
                    printf("nota do anime: 5 ou 6");
                }else{
                    printf("\nPrecisa existir? ");
                    scanf("%s", exist);
                    
                    if (strcmp(exist, "sim") == 0){
                        printf("Nota do anime: 4, 3 ou 2");
                    }else{
                        printf("Nota do anime: 1");
            }
        }
    }
}
    
    printf("\n\n\t\tFIM DO PROGRAMA!");
    
    return 0;
}
