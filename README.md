# calculatrice
#include <stdio.h>
#include <stdlib.h>
int main()
{
   //calculatrice
    //vars
    int nb1 = 0;
    int nb2 = 0;
    int operation = 0;
    char signe;
    //affichage
    printf("\t\t\tCALCULATRICE");
    printf("\n\n");
    printf("\n\n");
    printf("1)addition \n");
    printf("2)soustraction \n");
    printf("3)multiplication \n");
    printf("4)division \n");
    printf("\n\n");
    printf("CHOISISSEZ VOTRE TYPE D'OPERATION.");
     scanf("%d",&operation);
     printf("ENTREZ VOTRE PREMIER NOMBRE: ");
        scanf("%d",&nb1);
     printf("ENTREZ VOTRE SECOND NOMBRE: ");
        scanf("%d",&nb2);
     printf("\n\n");
     if (operation == 1) {
        signe = '+';
        printf("LE RESULTAT EST : %d ",nb1 + nb2);
     }
     else if (operation == 2){
        signe = '-';
       printf("LE RESULTAT EST : %d ",nb1 - nb2);
     }
      else if (operation == 3){
        signe = '*';
        printf("LE RESULTAT EST :%d ",nb1 * nb2);
     }
     else if (operation == 4){
        signe = '/';
        printf("LE RESULTAT EST :%d ",nb1 / nb2);
     }
      else {
        printf("ERREUR DE CHOIX D'OPERATION.");
        return 24;
     }
}
