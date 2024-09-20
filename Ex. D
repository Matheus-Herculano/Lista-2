#include <stdio.h>
void main()
{
    float n1, n2, n3, n4, md1, md2, ne;

    printf("Insira sua primeira mencao: ");
    scanf("%f", &n1);

    printf("Insira sua segunda mencao: ");
    scanf("%f", &n2);

    printf("Insira sua terceira mencao: ");
    scanf("%f", &n3);

    printf("Insira sua quarta mencao: ");
    scanf("%f", &n4);

    md1 = (n1+n2+n3+n4)/4;

    if(md1>=7)
    {
        printf("Aprovado(a)");
    }

    else
    {
        printf("Insira a quinta nota (nota de exame): ");
        scanf("%f", &ne);

        md2 = (md1+ne)/2;

        if(md2>=5)
        {
            printf("Aprovado(a) em exame, media: %f", md2);
        }
        else
        {
            printf("Reprovado(a), media: %f", md2);
        }
    }
}
