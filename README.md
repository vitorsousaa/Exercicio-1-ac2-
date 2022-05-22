# Exercicio-1-ac2-
import java.util.Scanner;

public class ac2 {

    public static void main(String[] args) {
         Scanner ler= new Scanner(System.in);
            int ra;
            double n1, n2, n3, m;
            int i, cont = 0;
            for (i = 0; i < 10; i++);
            cont++;
            System.out.printf("Digite o RA do aluno, se nao houver digite 0  ");
             ra = ler.nextInt();
             System.out.printf("Digite a primeira nota  ");
             n1 = nextDouble();
              System.out.printf("Digite a segunda nota  ");
             n2 = nextDouble();
              System.out.printf("Digite a terceira nota  ");
             n3 = nextDouble();

             m = (n1+n2+n3)/3;

             if (m>6) {
             System.out.printf("Voce foi reprovado  " + m);
             }

             else if (m>6 && m < 8) {
                 System.out.printf("Voce esta de recuperacao  " + m);
             }

             else {
                System.out.printf("Voce esta aprovado  ");
             }
        }

    private static double nextDouble() {

        return 0;
    }

    }
    
    
    ![media ac2](https://user-images.githubusercontent.com/103973613/169720905-c83588b4-d4cf-4492-baff-dad3799846e5.png)

