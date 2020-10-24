package EjercicioFibonacci;
import java.util.Scanner;
/**
 *
 * @author Mauricio
 */
public class ComplejoFibonacci {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Introduzca el número de posicionamiento de la serie de Fibonacci que quieres que busquemos: ");
        int n = sc.nextInt();
        double formula1 = ((1 + Math.sqrt(5))/2);
        var f1 = 1;
        double pot1 = 1;
        while(f1 <= n){
            pot1 *= formula1;
            f1++;
        }
        System.out.println(pot1);
        double formula2 = 1 - ((1 + Math.sqrt(5))/2);
        System.out.println(formula2);
        var f2 = 1;
        double pot2 = 1;
        while(f2 <= n){
            pot2 *= formula2;
            f2++;
        }
        System.out.println(pot2);
        double preResult = pot1 - pot2;
        double resultado = preResult / (Math.sqrt(5));
        System.out.println(resultado);
    }
}
