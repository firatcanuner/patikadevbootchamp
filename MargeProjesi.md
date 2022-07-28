# patikadevbootchamp
11.bootchamp hazırlık programı repo
Veri Yapıları ve Algoritmalar Merge Sort Projesi

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


Cevap 1:  sayılar 3'erli gruplara ayrılır ve her grup kendi içinde tek gruplar haline gelir.
Küçükten büyüğe doğru tekrar kendi aralarında grup oluşturarak sonuca ulaşılır

           16-21-11-8-12-22
     
     16-21-11               8-12-22
     
     16  21-11              8   12-22

     16  21 11              8   12 22
     
     16   11-21             8-12-22
     
     11-16-21               8-12-22
     
           [8-11-12-16-21-22]
           
           
 Soru 2- O(nlogn)
