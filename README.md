# Porcentajes
Programa llamado Porcentajes, en donde se le darán valor a dos variables llamadas a y b, posteriormente se obtendrá el porcentaje de ellos. 

package porcentajes;

import java.util.Scanner;

/**
 *
 * @author AudiGS
 
 */

public class Porcentajes {
    
public static void main(String[]args){
    int num;
        int porcentaje;
        double rpta;
                
        Scanner scanner = new Scanner(System.in);        
        System.out.print("Ingrese un numero para a: ");   
        num = scanner.nextInt();
        System.out.print("Ingrese un numero para b: ");   
        num = scanner.nextInt();
        System.out.print("Ingrese el porcentaje de a (%): ");   
        porcentaje = scanner.nextInt();
        System.out.print("Ingrese el porcentaje de b (%): ");   
        porcentaje = scanner.nextInt();
        rpta = num*porcentaje /100.0;
        System.out.println("El " + porcentaje+ " % de a "+ 
                num + " es " + rpta); 
        rpta = num*porcentaje /100.0;
        System.out.println("El " + porcentaje + " % de b "+ 
                num + " es " + rpta); 


    }
      
   
           
}
