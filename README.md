# dkp
1.Try to find out whether Main() function is predefined or user defined ?

--> Main() Function is Predefined Function but The body or logic inside the main method is user-defined.


2.if else concept using grade program.

import java.util.*;

public class Task1 {
    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);
        System.out.println("Enter a Marks");
        int marks=scanner.nextInt();
        char grade;

        if (marks >= 90) {
            grade = 'A';
        }
        else if (marks >= 80) {
            grade = 'B';
        }
        else if (marks >= 70) {
            grade = 'C';
        }
        else if (marks >= 60) {
            grade = 'D';
        }
        else {
            grade = 'F';
        }

        System.out.println("The grade for Marks " + marks + " is: " + grade);
    }
}

3.Loop Statement

 (a)For loop:

   public class ForLoopExample {
    public static void main(String[] args) {

        for (int i = 1; i <= 5; i++) {
            System.out.println(i);
        }
    }
}

 (b)While loop:

   public class WhileLoopExample {
    public static void main(String[] args) {
        int i = 1;
        while (i <= 5) {
            System.out.println(i);
            i++;
        }
    }
}

  (c)Do-While loop:


   public class DoWhileLoopExample {
    public static void main(String[] args) {
        int i = 1;

        do {
            System.out.println(i);
            i++;
        } while (i <= 5);
    }
}


3.Divide the two number(TypeCast)

  import java.util.*;
public class Divide {
    public static void main(String[] args) {
         Scanner scanner=new Scanner(System.in);
         System.out.println("Enter a Number");
         int a=scanner.nextInt();
         System.out.println("Enter a Marks");
         int b=scanner.nextInt();
         float c;
         c=(float)a/b;
         System.out.println(c);

        
    }
}
 
