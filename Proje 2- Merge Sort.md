# Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

## 1- Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Merge Sort, öncelikle diziyi ortasından ayırıp daha sonra dizinin elemanlarını yalnız ele alacak şekilde bu ayırmalara devam ederek bu sayıları karşılaştırıp en küçüğü başa gelecek şekilde birleştirmeyi amaç edinen bir uygulamadır. Bu şekilde ilerlediği için Insertion Sort'tan daha performanslıdır. Buna göre aşamalara bakalım;

### 1. Aşama
                         [16,21,11]     [8,12,22]
İlk aşamamızda diziyi ortadan ikiye böldük.

### 2. Aşama
                      [16] [21,11]       [8,12] [22]
Bölme işlemini tekrar gerçekleştiriyoruz.

### 3. Aşama
                     [16] [21] [11]      [8] [12] [22]
Elde ettiğimiz bu yapıyı tekrar birleştirme aşamasına geçiyoruz. Birleştirirken sayıları karşılaştırıp küçük olma durumunu göz önünde bulundurarak sıralama yapıyoruz.

### 4. Aşama

                      [16] [11,21]      [8,12] [22]
### 5. Aşama

                         [11,16,21] [8,12,22]
Son birleştirme işlemi gerçekleşiyor.


### Sonuç : 
                           [8,11,12,16,21,22]

## 2- Big-O gösterimini yazınız.

O(nlogn)