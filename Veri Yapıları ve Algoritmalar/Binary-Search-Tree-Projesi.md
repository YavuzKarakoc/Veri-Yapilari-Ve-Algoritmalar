## soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap
```
Öncelikle  [7,5,1,8,3,6,0,9,4,2] dizimizi  sıralı hale getirelim

sıralı hali  [0,1,2,3,4,5,6,7,8,9,]  olan dizimizin ortadaki terimini  root değeri olarak seçelim bu değer ya 4 ya da 5
olabilir. Seçimi yapıp sıralayalım. 4'ü  Root değer olarak seçersek  4'den küçük sayıları sola  büyük sayıları  sağa 
yazarız. 4'ün  soluna 2 sağına  7. 2'nin soluna 1  sağına 3. 1'in soluna 0.  4'ün sağındaki  7 nin soluna 6 sağına 8.
6'nın soluna 5. 8'in  sağına da 9 yazarız.Ve binary serarh tree mizi tamamlamış oluruz



                           4

                2                      7

            1       3              6         8

      0                       5                   9

```        


