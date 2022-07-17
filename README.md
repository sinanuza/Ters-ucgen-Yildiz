# Ters-ucgen-Yildiz
www.patika.dev ters ucgen yildiz





import java.util.Scanner;

public class Ters_ucgen {
    public static void main(String[] args) {
        int basamak;
        System.out.println("Lutfen basamak sayisi giriniz:");
        Scanner input =new Scanner(System.in);
        basamak=input.nextInt();
        int bosluk=0;
        int yildiz=((2*basamak)-1);
        for (int a=1;a<=basamak;a++) {
            for (int i = 0; i <= (bosluk); i++) {
                System.out.print(" ");
            }
                for (int j = 1; j <= yildiz; j++) {
                    System.out.print("*");
                }
            System.out.println();
            bosluk++;
            yildiz -= 2;
            }
        }
    }
