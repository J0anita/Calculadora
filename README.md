# Calculadora
 Calculadora simples, apenas precisando inserir valores.
 Calcula automaticamente adição, subtração, multiplicação e divisão.

import java.util.Scanner;

public class Calc {
    public static void main(String[] args) {
        int n1;
        int n2;
        Scanner input = new Scanner(System.in);

        System.out.println("Qual o primeiro numero?");
        n1 = input.nextInt();
        System.out.println("Qual o segundo numero?");
        n2 = input.nextInt();

        System.out.println("Soma:" + (n1 + n2));
        System.out.println("Sub:" + (n1 - n2));
        System.out.println("Divisao:" + (n1 / n2));
        System.out.println("Multiplicacao:" + (n1 * n2));
    }
}