# Java-input-results
#a set of codes put together and gives the user a chance to input, name, marks and tells the grade of the user, once its runs.

import java.util.Scanner;
public class Example {
  public static void main (String [] args ) {
    
     Scanner jaguars= new Scanner (System.in);
     System.out.println("Enter the your name");
       String name = jaguars.nextLine();
    
    
     Scanner bj= new Scanner (System.in);
     System.out.println("Enter the marks for your units");
      int a = bj.nextInt();
      int b =bj.nextInt();
      int c =bj.nextInt();
      int d =bj.nextInt();
      int e =bj.nextInt();
      int f =bj.nextInt();
      int g =bj.nextInt();
      int s =a+b+c+d+e+f+g;
  
   ;
      if( s >= 600) {
         System.out.print("You have an A");
      }else if( s >=500 ) {
         System.out.print("You have a B");
      }else if( s>= 350 ) {
         System.out.print("You have a C");
      }else {
        System.out.print("Bora uhai"); }
   
    
      System.out.println("  Sum of " + a + " and " + b + " and  " + c + " and " + d + " and " + e + " and " + f + " and " + g + " is " +s ); 
  }  }








