# codigo1
#include <stdio.h>
#include <stdlib.h>
int main()
{
    int i;
    for(i=1;i<=100;i++) // Laço for para contar de 1 a 100
    {
        if (i%3==0&&i%5==0) // utiliza a funcao resto para definir os multiplos dos numeros, e iniciando pelos multiplos de 3 e 5 ao mesmo tempo
        {
            printf("FooBaa\n"); // se o primeiro if for aceito, mostra na tela FooBaa
        }
        else if (i%5==0) // em seguida somente a funcao resto para o 5, mostrando seus multiplos
        {
            printf("Baa\n"); //se o primeiro não for aceito então vai para o laço else if, se aceito mostra na tela Baa
        }
        else if (i%3==0) //em seguida somente a funcao resto para o 3, mostrando seus multiplos
        {
            printf("Foo\n"); //se o segundo else if não for aceito então vai para o ultimo laço else if, se aceito mostra na tela Foo
        }
        else printf ("%i\n", i); // caso o numero nao seja multiplo nem de 3 ou 5 ele aparecera na tela normal
    }
    return 0;
}
