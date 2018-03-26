# java

import java.util.Scanner;

public class GrassHopper {

  public static int summation(int n) {
    if (n == 1) {
      return 1;
      }
    return (n + summation(n-1));
  }
  public static void main(String args[]) {
      Scanner sc = new Scanner (System.in);
      int i;
      i = sc.nextInt();
      System.out.println(summation(i));
   }
}
