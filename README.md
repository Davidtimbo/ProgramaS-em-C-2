# ProgramaS-em-C-2 
(Agora estou aprendendo Java, e aos poucos vou postando alguns códigos para ver a evolução)
Alguns programas/códigos que fiz em C


        // Descobrir hora mensal//
    
          #include <stdio.h>
          int main()  {
      
     
        int horas, semanas, dias, resultado;
        printf("Digite suas horas trabalhadas ao dia: ");
         scanf("%d",&horas);
      
         printf("Digite seus dias trabalhados na semana: ");
         scanf("%d",&dias);
      
         printf("Digite quantas semanas trabalha no mês: ");
         scanf("%d",&semanas);
      
         resultado = horas*dias*semanas;
         printf("%d horas no mês.",resultado);
      
       }
       
       
       
        /*descobrir idade e diz se é ou nao menor de idade*/
         
              #include <stdio.h> 
              int main()
            {
              int ano, nasc, idade;

            printf("Que ano você nasceu?\n");
            scanf("%d",&nasc);

            printf("Em que ano estamos?\n");
            scanf("%d",&ano);

          idade = ano-nasc;
            printf("Em %d vocêc vai ter %d!\n",ano,idade);

            if (idade > 18)
              printf("\nParabens, você já é maior de idade");

           else if 
           (printf("Você ainda é menor de idade"));

           }
           
           
           
                /*PARA DESCOBRIR SE É PAR OU IMPAR*/ 

          #include <stdio.h>

          int main(void) {

          int num;

            printf("Digite um número para descobir se é PAR ou IMPAR:\n");
                  scanf("%d",&num);

            if (num % 2 == 0)
                printf("O numero %d é PAR\n", num);

             else if (printf ("O número %d é IMPAR\n"));

          }


    

               /*APTO OU NAO PARA TIRAR CARTEIRA DE MOTORISTA PELA IDADE*/ 

              #include <stdio.h>
            
              int main () {

                int at,anon,idade;

                  printf("-------------------------\n");
                  printf("Departamento de Transito\n");
                  printf("-------------------------\n\n");

                  printf ("Ano atual -> ");
                  scanf("%d",&at);

                  printf("Ano de nascimento -> ");
                  scanf("%d",&anon);

                  printf("\n---------STATUS---------\n");

                idade= at-anon;
                printf("Idade:%d\n",idade);

                  if (idade >= 18)
                    printf ("Apto(a) a tirar a carteira.\n");

                  if (idade <18)
                printf("Inapto(a) a tirar a carteira.\n"); 
              {
                printf("------------------------");}
              }




        #include <stdio.h>

        int main () {


         float media,nota1,nota2;

            printf("-------------------------\n");
            printf("Escola CP2\n");
            printf("-------------------------\n\n");

            printf ("Primeira nota -> ");
            scanf("%f",&nota1);

            printf("Segunda nota -> ");
            scanf("%f",&nota2);

          printf("\n---------STATUS---------\n");

          media = (nota1 + nota2) / 2;
          printf("Média:%.2f\n",media);

            if  (media >= 7)
              {
              printf ("Aluno aprovado! Parabénss! \n");
              }

            else {
              if (media >= 5) 
              {
         printf("Aluno em recuperação. Boa sorte! \n"); 
                }

            else {  
          printf("Aluno reprovado. Na próxima você consegue! \n");
              }
                }

        {
          printf("------------------------");
          }
         }





          \\ESTRUTURA FOR\\ 

        #include <stdio.h>
        #include <stdlib.h>
        #include <string.h>

        int main () {

          int cont;
          float total,nota,media;
          char cod;
          cod = 'C';
          total = 0;
          while (cod != 'F') { 
            for(cont=1;cont<=4;cont++) { 
              printf("\nDigite a nota do aluno: ");
              scanf("%f",&nota);
              total+=  nota;   
            }

           media = total / 4;
            printf("\nMédia %.2f\n",media);
            total = 0;
            nota = 0;

          printf("\n\n Se deseja finalizar, pressione a tecla 'F', caso contrario aperte qualquer tecla!\n");

            }
         return 0;
           }











           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
