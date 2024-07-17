import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
    
     Scanner input= new Scanner(System.in);
     
     int sayi;
     
     System.out.print("Basamak sayısını giriniz: ");
     
     sayi=input.nextInt();

     for(int i=1;i<=sayi;i++){
     

         for(int k=1;k<=(sayi-i);k++){
         
             System.out.print(" ");
             
         }
     }
     for(int j=1;j<=(2*i)-1;j++){
     
         System.out.print("*");
     }



    }
}
