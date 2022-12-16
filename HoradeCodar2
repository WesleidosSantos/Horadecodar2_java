//Exercício 1

import java.util.Scanner;

public class HoraDeCodarDois {
    public static void main(String[] args) {
        Scanner exercício1 = new Scanner(System.in);
        while (true){
            System.out.println("Digite um nuemro: ");
            int numero = exercício1.nextInt();

            if(numero > 0){
                System.out.println("O numero é positivo");
            } else if (numero == 0){
                System.out.println("O numero é zero");
            } else {
                System.out.println("O numero é negativo");
            }

            exercício1.close();
        }
    }
}

//Exercício 2

public class Exercicio2 {
    public static void main(String[] args) {

        while(true){
            Scanner Exercicio2 = new Scanner(System.in);

            System.out.println("Digite o 1° numero: ");
            double num1 = Exercicio2.nextDouble();
            System.out.println("Digite o 2° numero: ");
            double num2 = Exercicio2.nextDouble();
            System.out.println("Digite o 3° numero: ");
            double num3 = Exercicio2.nextDouble();


            if(num1 > num2 && num1 > num3){
                System.out.println("O maior numero é o : "  + num1);
            }
            if(num2 > num1 && num2 > num3){
                System.out.println("O maior numero é o : "  + num2);
            }
            if(num3 > num2 && num3 > num1){
                System.out.println("O maior numero é o : "  + num3);
            }

            Exercicio2.close();

        }
    }
}

//Exercício 3

public class Exercicio3 {
    public static void main(String[] args) {
        Scanner Exercicio3 = new Scanner(System.in); 
        int valor1;
        int valor2; 
        int valor3;

        System.out.println("Digite o 1° numero: ");
        valor1 = Exercicio3.nextInt();

        System.out.println("Digite o 2° numero: ");
        valor2 = Exercicio3.nextInt();

        System.out.println("Digite o 3° numero: ");
        valor3 = Exercicio3.nextInt();


        

         if(valor1 < valor2 && valor1 < valor3) {
            System.out.println("A soma dos maiores numeros foi de: " + (valor2 + valor3));
         }
         else if (valor2 < valor1 && valor2 < valor3) {
            System.out.println("A soma dos maiores numeros foi de: " + (valor1 + valor3));
         }
         else {
            System.out.println("A soma dos maiores numeros foi de: " + (valor1 + valor2));
         }

         Exercicio3.close();

    }

}

//Exercício 4

public class Exercicio4 {
    public static void main(String[] args) {
       Scanner Exercicio4 = new Scanner(System.in); 
       
       int total = 0;
       
       for (int i = 0; i < 10; i++) {

           System.out.println("Digite um valor: ");
           int n1 = Exercicio4.nextInt();
           total += n1;
       }

       System.out.println("A média artimética desses 10 valores foi de: " + (total / 10));
           
}
}

//Exercício 5
public class Exercicio5 {
    public static void main(String[] args) {
        Scanner Exercicio5 = new Scanner(System.in);
        double soma = 0;

        for (int i = 0; i < 4 ; i++) {
            System.out.println("Digite uma nota");
            double nota = Exercicio5.nextDouble();
            soma += nota;
        }

        double media = soma / 4;

        if(media >= 6){
            System.out.println("Voce foi aprovado!");
        } else {
            System.out.println("Voce foi reprovado");
        }
    }
}

public class Exercicio5 {
    public static void main(String[] args) {
    Scanner Exercicio5 = new Scanner(System.in); 
    int n1, n2, n3, n4;
    int res;

    System.out.println("Informe a primeira nota do aluno: ");
    n1 = Exercicio5.nextInt();
    Math.round(n1);

    System.out.println("Informe a segunda nota do aluno: ");
    n2 = Exercicio5.nextInt();
    

    System.out.println("Informe a terceira nota do aluno: ");
    n3 = Exercicio5.nextInt();
    

    System.out.println("Informe a quarta nota do aluno: ");
    n4 = Exercicio5.nextInt();
    
    res = (n1 + n2 + n3 + n4) / 4;
    
    if (res >= 6 && res <= 10) {
        System.out.println("Voce foi aprovado!");
    }
    else if (res < 6 && res >= 0) {
        System.out.println("Voce foi reprovado");
    }
     
    }
}
