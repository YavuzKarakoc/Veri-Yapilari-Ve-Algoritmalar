## Soru 1 
[22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.
* Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Cevap 1
```
1. [22,27,16,2,18,6]
2. [2,27,16,22,18,6]
3. [2,6,16,22,18,27]
4. [2,6,16,18,22,27]  son aşaması

Big-O gösterimi

n+(n-1)+(n-2).....+1 =n.(n+1)/2 
(n^2 + n)/2 = O(n^2)

Time complexity
average case : [6,16,18,22]  O(n^2 /2)
worst case   : [27]     O(n^2)
best case    : [2]     O(1)


18 sayısı üstteki cevapda da belirtildiği gibi average case kapsamına girer.

```

## Cevap 2
```
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]  aşama 1  2 ile 7 yer değişti
[2,3,4,8,7,9,5,15,6]  aşama 2  4 ile 5 yer değişti
[2,3,4,5,7,9,8,15,6]  aşama 3  5 ile 8 yer değişti
[2,3,4,5,6,9,8,15,7]  aşama 4  6 ile 7 yer değişti
```
