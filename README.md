import java.util.Scanner;
public class Main {
public static void main(String[] args){
// Değişkenlerimizi oluşturalım.
int a , b;
double c;

       // Kullanıcıdan verilerimizi alalım.
       Scanner girdi = new Scanner(System.in);
       System.out.println("1.Kenarı Giriniz :  ");
       a  = girdi.nextInt();
       System.out.println("2.Kenarı Giriniz :  ");
       b = girdi.nextInt();


       c = Math.sqrt((a*a)+ (b*b));
       System.out.println("Hipotenüs: " + c );
    }
}
