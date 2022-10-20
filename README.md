[Patika.dev](https://www.patika.dev/tr)'in Veri Yapıları ve Algoritmalar eğitiminin ilk projesidir.

[22,27,16,2,18,6] -> Insertion Sort
1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
[2,27,16,22,18,6] En küçük sayının 2 olduğunu belirledik. 2 ve 22 yer değiştirdi.
[2,6,16,22,18,27] 2 haricinde en küçük sayı 6. 6 ve 27 yer değiştirdi.
[2,6,16,22,18,27] 16 üçüncü en küçük sayı olduğundan yer değiştirilmedi.
[2,6,16,18,22,27] 18 ve 22 yer değiştirdi.
[2,6,16,18,22,27] istenen sıralama bulunduğundan yer değiştirilmedi.
2.Big-O gösterimini yazınız.
O(n^2)
3.Time Complexity:
Average Case:Aradığımız sayının ortada olması
Worst Case:Aradığımız sayının sonda olması
Best Case:Aradığımız sayının dizinin en başında olması
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Aradığımız sayı başta ve sonda bulunmadığı için average case kapsamına girer.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[2,3,5,8,7,4,15,6] En küçük sayı 2 bulundu. 2 ve 7 yer değişti.
[2,3,5,8,7,4,15,6] 3 olması gerektiği yerde olduğundan sabit kaldı.
[2,3,4,8,7,5,15,6] 4 ve 5 yer değişti.
[2,3,4,5,7,8,15,6] 5 ve 8 yer değişti.
