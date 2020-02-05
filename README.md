# Contador
package contador;

/**
 *
 * @author USUARIO
 */
public class Contador {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        double n=0;
        for(double i = 1; i <= 100000000;)
        {
            n = n+i;
            i = i + 2;
        }
        System.out.println(n);
    }
