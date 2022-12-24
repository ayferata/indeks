# indeks
package day01;

import java.util.Scanner;

public class day4 {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);

        System.out.print("Lütfen boyunuzu metre cinsinden giriniz= ");
        double boy = scan.nextDouble();

        System.out.print("Lütfen kilonuzu giriniz= ");
        double kilo = scan.nextDouble();

        double indeks = kilo / (boy*boy);
        System.out.print("Vücut Kitle İndeksiniz= "+indeks);
        

    }
}
