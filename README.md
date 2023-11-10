# 05Faccat
05Faccat

package exercicios;

import java.util.Scanner;

public class Exercicio05Faccat {

	public static void main(String[] args) {
		System.out.println("Digite um valor para saber o seu antecesso :");

		Scanner sc = new Scanner(System.in);
		
		int valor= sc.nextInt();
		int antecessor=valor-1;
		
		System.out.println("O antecessor do numero digitado é :" + antecessor);
	}

}
