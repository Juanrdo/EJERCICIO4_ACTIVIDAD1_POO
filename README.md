# EJERCICIO4_ACTIVIDAD1_POO

package cuadradoycubo;
import java.util.Scanner;
public class Cuadradoycubo {

    public static void main(String[] args) {
        double numero,cuadrado,cubo;
        Scanner teclado = new Scanner (System.in);
        
        System.out.println("Ingrese el numero:  ");
        numero = teclado.nextDouble();
        cuadrado= Math.pow (numero,2);
        cubo= Math.pow (numero,3);
        
        System.out.println("el numero es: "+ numero);
        System.out.println("el cuadrado es :  "+ cuadrado);
        System.out.println("el cubo es :  "+ cubo);
    }
    
}
