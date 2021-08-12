# URI-online-judge
This repository contains URI online judge exercises.

URI 1003 JAVA - Soma simples

import java.io.IOException;
import java.util.Scanner;
 
public class Main {
 
    public static void main(String[] args) throws IOException {
      Scanner input = new Scanner(System.in);
      
      int A = input.nextInt();
      int B = input.nextInt();
      int SOMA = A + B;
      
      System.out.println("SOMA = " + SOMA);
      
      input.close();
    }
 
}

URI 1004 JAVA - Produto simples

import java.io.IOException;
import java.util.Scanner;
 
public class Main {
 
    public static void main(String[] args) throws IOException {
        Scanner input = new Scanner(System.in);
        
        int n1 = input.nextInt();
        int n2 = input.nextInt();
        int PROD = n1 * n2;
        
        System.out.println("PROD = " + PROD);
    }
 
}

URI 1005 JAVA - Média 1

import java.io.IOException;
import java.util.Scanner; 

public class Main {
 
    public static void main(String[] args) throws IOException {
        Scanner input = new Scanner(System.in);
        
        double A = input.nextDouble();
        double B = input.nextDouble();
        double MEDIA = ((A * 3.5) + (B * 7.5)) / 11.0;
        
        System.out.printf("MEDIA = %.5f%n", MEDIA);


        input.close();
    }
 
}

URI 1006 JAVA - Média 2

import java.io.IOException;
import java.util.Scanner;
 
public class Main {
 
    public static void main(String[] args) throws IOException {
        Scanner input = new Scanner(System.in);
    
        double A = input.nextDouble();
        double B = input.nextDouble();
        double C = input.nextDouble();
        double MEDIA = ((A * 2.0) + (B * 3.0) + (C * 5.0)) / 10.0;
    
        System.out.printf("MEDIA = %.1f%n", MEDIA);
        input.close();
    }
 
}

URI 1007 JAVA - Diferença

import java.io.IOException;
import java.util.Scanner; 

public class Main {
 
    public static void main(String[] args) throws IOException {
       Scanner input = new Scanner(System.in);
       
       int A = input.nextInt();
       int B = input.nextInt();
       int C = input.nextInt();
       int D = input.nextInt();
       
       int DIFERENCA = ((A * B) - (C * D));
       
       System.out.println("DIFERENCA = " + DIFERENCA);
       input.close();
    }
 
}

URI 1008 JAVA - Salário


URI 1009 JAVA - Sslário com Bonus

import java.io.IOException;
import java.util.Scanner; 

public class Main {
 
    public static void main(String[] args) throws IOException {
         Scanner input = new Scanner(System.in);
         
         String nomeVendedor = input.next();
         double salarioFixo = input.nextDouble();
         double vendasEfetuadas = input.nextDouble();
         double comissao = vendasEfetuadas * 0.15;
         double salarioFinal = salarioFixo + comissao;
                  

         System.out.printf("TOTAL = R$ %.2f%n", salarioFinal);
         
         input.close();
    }
 
}

URI 1010 JAVA - Cálculo simples

import java.io.IOException;
import java.util.Scanner; 
 
public class Main {
 
    public static void main(String[] args) throws IOException {
         Scanner input = new Scanner(System.in);
         
         int codigoPeca1 = input.nextInt();
         int qtdPeca1 = input.nextInt();
         double valorPeca1 = input.nextDouble();
         int codigoPeca2 = input.nextInt();
         int qtdPeca2 = input.nextInt();
         double valorPeca2 = input.nextDouble();
         
         double custoTotal = qtdPeca1 * valorPeca1 + qtdPeca2 * valorPeca2;

         System.out.printf("VALOR A PAGAR: R$ %.2f%n", custoTotal);
         
         input.close();
    }
 
}

URI 1011 JAVA - Esfera

