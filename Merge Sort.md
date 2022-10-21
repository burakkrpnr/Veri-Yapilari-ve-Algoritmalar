# Merge Sort Projesi

## [Patika.Dev](https://www.patika.dev/tr), [Burak Karapınar Patika](https://app.patika.dev/brkkrpnr)
###  [16,21,11,8,12,22] -> Merge Sort
### _1-)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız._
Diziyi ikili hallerde tek tek bölerek tüm sayılar yalnız kalana kadar devam ediyoruz.
|İlk Olarak Diziyi İkiye Bölüyoruz.     | |16|21|11|  |  |8 |12|22|  |
| :-                                  | --- |---  | --- | --- | --- | --- | --- | ---| --- | --- |
|Tekrar ikiye bölerek devam ediyoruz.   |  16| 21  | 11 |  |  |8 |  |12 | 22|  |
|Tek eleman kalana kadar bir kez daha bölüyoruz.  |  |16|21|  |11|  |  |8 |  |12|22|  |
|                                                 |16|  |21|  |11|  |  |8 |  |12|  |22|

Bölme işlemlerinden sonra diziyi tekrar ilk haline gelene kadar toplayarak ilerliyoruz.
| 1.Aşama  |  |16|21|  |11|  |  |8 |  |12|22|  |
|:----------------------------------------------- |- |- |- |- |- |- |- |- |- |- |- |- |
|2.Aşama |  |  |11|16|21|  |  |8 |12|22|  |  |
|Son adım.     | | | |8 |11|12|16|21|22| | | |
### _2. Big-O gösterimini yazınız._
O(n*(logn)) --> O(6*(log6)) olacaktır.
