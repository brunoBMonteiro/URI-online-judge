# URI-online-judge
This repository contains URI online judge exercises.

URI 1003 JAVA

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

URI 1004 JAVA

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
