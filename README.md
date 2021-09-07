import java.util.Scanner;
public class Swap1{

  public static void main (String[]args)
  {
    int a=10;
    int b=20;

    System.out.println("value of a="+a);
    System.out.println("value of b="+b);
    System.out.println("after Swapping");
    
    a=a+b;
    b=a-b;
    a=b-a;
    System.out.println("value of a="+a);
    System.out.println("value of b="+b);

   }
 }
