# curso-java-basico-dio
Repositorios para exemplos e exercicios da DIO

Codigo Calculo com impressão de Numero e Média 

------------------------------------------------------------------------------------



package ExerciciosDio;

import java.util.Scanner;


public class MaiorMedia {

public static void main(String[]args){

    Scanner scan = new Scanner(System.in);

    int numero;
    int maior = 0;
    int soma = 0;

    int count = 0;
     do{
         System.out.println("Numero: ");
         numero = scan.nextInt();

         soma = soma + numero;



         System.out.println("Soma: "+ soma);

     if (numero > maior) maior = numero;

     count = count + 1;

     } while(count < 5);

     System.out.println("Numero:" + maior);
    System.out.println("Media:" + soma/5);

}


}




