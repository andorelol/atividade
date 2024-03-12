import java.util.Scanner;

public class SomaDosNumeros {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Digite o primeiro número: ");
        int num1 = scanner.nextInt();
        System.out.println("Digite o segundo número: ");
        int num2 = scanner.nextInt();
        int soma = num1 + num2;
        System.out.println("A soma dos dois números é: " + soma);
        scanner.close();
    }
}


import java.util.Scanner;

public class ParOuImpar {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Digite um número inteiro: ");
        int num = scanner.nextInt();
        if (num % 2 == 0) {
            System.out.println(num + " é um número par.");
        } else {
            System.out.println(num + " é um número ímpar.");
        }
        scanner.close();
    }
}


import java.util.Scanner;

public class MediaDosNumeros {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Digite o primeiro número: ");
        double num1 = scanner.nextDouble();
        System.out.println("Digite o segundo número: ");
        double num2 = scanner.nextDouble();
        System.out.println("Digite o terceiro número: ");
        double num3 = scanner.nextDouble();
        double media = (num1 + num2 + num3) / 3;
        System.out.println("A média dos três números é: " + media);
        scanner.close();
    }
}


//ATIVIDADE//
Os números são iguais?
Crie uma função que retorne truequando xfor igual a y; caso contrário, retorne false.

Exemplos
isSameNum(4, 8) ➞ false

isSameNum(2, 2) ➞  true

isSameNum(42, 32) ➞  false
Notas
Não se esqueça do returnresultado.



Calculadora de potência
Crie uma função que receba voltagee currentretorne a potência calculada .

Exemplos
power(230, 10) ➞ 2300

power(110, 3) ➞ 330

power(480, 20) ➞ 9600
Notas
N / D


