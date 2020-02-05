Bu sayfada indirmeyi başaramıyanlar için kodun birebir aynısıbulunmaktadır
instagram:Gunruy.offical
-----------------------
not: bu kodu yazmadan önce scanner kütüphanesini import etmelisiniz 
import java.util.Scanner;   
ile yapılacak
-------------------------
yeni bir class oluştururken seçeneklerden public static void main(strings[] args) kutucuğunu işaretlemeyi unutmayınız

-------------------------
//açıklama satırı demektir koda bir etkisi yoktur koda bakan kişinin bilmesi gereken bir bilgiyi 
kullanıcıya kod aracılığıyla sunmak için kullanılır.
açıklama satırları kod yazarken unutmamanız gereken şeyleri not almanızı sağlar 
-------------------------
int sayi,x=1,y=1,z,tersi=0;    //y basamak sayısı
		 Scanner gir = new Scanner (System.in);    
		 System.out.println("sayi : ");      
		 sayi = gir.nextInt();
		 while (sayi/x>9)
		 {         
			 x=x*10;         
			 y++;         
			 }
		 
		 
	        for(;sayi != 0; sayi /= 10) {
	            int basamak = sayi % 10;
	            tersi = tersi * 10 + basamak;
	        }
        System.out.println(tersi);
       
       
       
	}
