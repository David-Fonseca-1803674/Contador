# Contador u1803674
package contador;
public class Contador {
   public static void main(String[] args) {
        double n=0;
        for(double i = 1; i <= 100000000;)
        {
            n = n+i;
            i = i + 2;
        }
        System.out.println(n);
    }
