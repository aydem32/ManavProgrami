import java.util.Scanner;

public class ManavProgrami {

    public static void main(String[] args){

        Scanner input = new Scanner(System.in);

        double armut,elma,domates,muz,patlican;
        armut = 3.4;
        elma = 2.8;
        domates = 4.5;
        muz = 9;
        patlican = 3;

        System.out.println("Armut Kaç Kilo");
        double arm = input.nextFloat();
        System.out.println("elma Kaç Kilo");
        double elm = input.nextFloat();
        System.out.println("domates Kaç Kilo");
        double dom = input.nextFloat();
        System.out.println("muz Kaç Kilo");
        double muzz = input.nextFloat();
        System.out.println("Patlican Kaç Kilo");
        double pat = input.nextFloat();

        double sonuc;
        sonuc = (armut*arm)+(elm*elma)+(dom*domates)+(muzz*muz)+(pat*patlican);
        System.out.println("Toplam Tutar : " + sonuc);





    }




}
