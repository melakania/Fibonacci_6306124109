Fibonacci_6306124109
====================
package Fibonacci;
import java.util.Scanner;
/**
 *
 * @author Praktikum
 */
public class Fibonacci
{
    public static void main(String[] args)
    {
        int f = 0;
        int g = 1;
        Scanner input = new Scanner (System.in);
        System.out.print("Input Angka: ");
        int a=input.nextInt();
        System.out.print("Hasil: ");
        for(int i = 1; i <= a; i++)
        {
            f = f + g;
            g = f - g;
            System.out.println(f + " ");
        }

        System.out.println();
    }
}
