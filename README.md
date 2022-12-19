# pratikler3
dik kenarları kenarA ve kenarB olan üçgenin alanını ve çevresini hesaplama

import java.util.Scanner ;

public class dikÜcgen {
    public static void main(String[] args) {

        double kenarA ,kenarB ,kenarC , alan , cevre ;
        Scanner input = new Scanner(System.in) ;

        System.out.print("KenarA: " );
        kenarA = input.nextInt();

        System.out.print("KenarB: " );
        kenarB = input.nextInt();

        System.out.print("KenarC: " );
        kenarC = input.nextInt();

        cevre = kenarA + kenarB + kenarC ;
        alan = (kenarA * kenarB) / 2 ;

        System.out.println("ÇEVRE: " + cevre);
        System.out.print("ALAN: " + alan);



    }
}
