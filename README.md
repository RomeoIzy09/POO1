# POO1
POO_ romeo_ITCK _2Semester
package balancegeneral;

import java.util.Scanner;

/**
 *
 * @author ariel
 */
public class BalanceGeneral {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        int activo, pasivo, contable, noContable;
        Scanner sc= new Scanner(System.in);
        int i=0;
        String y, n;
        do{
            System.out.println("BIENVENIDO AL SISTEMA DE BALANCE DE CUENTAS");
            System.out.println("===========================================");
            System.out.println("1) activo");
            System.out.println("2) pasivo");
            System.out.println("3) contable");
            System.out.println("4) no contable ");
            if(sc.nextInt()==1){
                System.out.println("dame el activo:");
                activo=sc.nextInt( );        
            }
            System.out.println("elige otra opcion:");
            if(sc.nextInt()==2){
                System.out.println("dame el pasivo:");
                pasivo=sc.nextInt();
            }
            System.out.println("elige otra opcion:");
            if(sc.nextInt()==3){
                System.out.println("dame el contable:");
                contable=sc.nextInt();
            }
            System.out.println("elige otra opcion:");
            if(sc.nextInt()==4){
                System.out.println("dame el no contable:");
                sc.nextInt();
            }
            System.out.println("ahora, que operacion te gustaria que realice el programa por ti:");
        }while(i>sc.nextInt());
        System.out.println("===========================================");    
    }   
}
   
