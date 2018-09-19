# Estudiante
Trabajo con tiempo de ejecucin 
package t05;

import java.util.Scanner;

/**
 *
 * @author 
 */
public class T05 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
       Scanner scan=new Scanner(System.in);
        //Variables declaradas
        long Ti,Tf,t;
        int N=1000000,Suma=0;
        //Hora de inicio de la ejecucion 
        Ti=System.currentTimeMillis();
         // Inicio de mi bucle for 
         for(int i=1; i<=N; i++)
         {
             Suma= Suma+i;
         }
         // Imprecion de suma 
         System.out.println("El Valor total es: "+Suma);
        // Hora final de ejecucion 
        Tf= System.currentTimeMillis();
        //Calculamos los milisegundos de diferencia
        t=Tf-Ti;
        System.out.println("El Tiempo de ejecucion en milisegundos es: "+t);
    }
    
}

