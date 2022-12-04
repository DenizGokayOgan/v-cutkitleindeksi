# vucutkitleindeksi

     import java.util.Scanner;
     public class Main {

    public static void main(String[] args) {
        double boy, kilo, indeks;

        Scanner input = new Scanner(System.in);
        System.out.println("Metre cinsinden boy giriniz: ");
        boy = input.nextDouble();
        System.out.println("Kilo giriniz: ");
        kilo =input.nextDouble();
        indeks = kilo / (boy*boy);

        System.out.println("Vücut kitle indeksiniz: " +indeks);


    }
}
