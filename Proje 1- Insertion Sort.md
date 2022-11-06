# Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


## 1- Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Öncelikle intertion sort, dizideki en küçük elemanı arar ve bu elemanı dizinin en solundaki eleman ile yer değiştirir. Daha sonra, sıradaki küçük elemanı arar ve sonraki sırayla yer değiştirir. Bu şekilde küçükten büyüğe doğru sıralama yapar.
Buna göre yukarıdaki dizinin aşamaları aşağıdaki gibidir;

### 1.Aşama

[2,27,16,22,18,6]

En küçük eleman olan 2'yi dizideki 22 sayısı ile değişimi gerçekleşir.

### 2.Aşama

[2,6,16,22,18,27]

Görüldüğü üzere, 2'den sonra en küçük olan 6 rakamını 2'den sonraki sıraya koyabilmek için 27 sayısıyla yer değiştiriyor.

### 3.Aşama

[2,6,16,18,22,27]

16, sıraya uyduğu için yeri değişmedi. 18 ve 22 yer değiştirerek sıralama tamamlanmış oldu.

Sonuç  : 
[2,6,16,18,22,27]

## 2- Big-O gösterimini yazınız.
 Worst Case: O(n^2)

 Average Case: O(n^2)

 Best Case: O(n)

 ## 3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

 
 ### Worst Case: 
 
 [27,22,18,16,6,2]

 
 ### Average Case:
 
 [6,16,22,2,18,27]

 
 ### Best Case:
 
 [2,6,16,18,22,27]


 ## 4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

 [2,6,16,18,22,27] 

 Dizinin sıralanmış hali bu şekildeydi. Buna göre 18, avarage case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]




