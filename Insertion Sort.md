[Patika.dev](https://www.patika.dev/tr)'in Veri Yapıları ve Algoritmalar eğitime ait ilk proje.<br/>(https://app.patika.dev/brkkrpnr)

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
<br/>[2,27,16,22,18,6] En küçük sayının 2 olduğunu belirledik. 2 ve 22 yer değiştirdi.
<br/>[2,6,16,22,18,27] 2 haricinde en küçük sayı 6. 6 ve 27 yer değiştirdi.
<br/>[2,6,16,22,18,27] 16 üçüncü en küçük sayı olduğundan yer değiştirilmedi.
<br/>[2,6,16,18,22,27] 18 ve 22 yer değiştirdi.
<br/>[2,6,16,18,22,27] istenen sıralama bulunmuştur.

2. Big-O gösterimini yazınız.<br/>O(n^2)

3. Time Complexity
 <br/>Best Case  = [2,6,16,18,22,27]
 <br/>Worst Case = [27,22,18,16,6,2]

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız:
    <br/>Aradığımız sayı başta ve sonda bulunmadığı için average case kapsamına girer.
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    <br/>[2,3,5,8,7,9,4,15,6] = En küçük sayı=2.> 2 ve 7 yer değişti.
    <br/>[2,3,4,8,7,9,5,15,6] = 5 ile 4 sayısı yer değiştirdi
    <br/>[2,3,4,5,7,9,8,15,6] = 8 ile 5 sayısı yer değiştirdi
    <br/>[2,3,4,5,6,9,8,15,7] = 6 ile 7 sayısı yer değiştirdi

 
 
 
