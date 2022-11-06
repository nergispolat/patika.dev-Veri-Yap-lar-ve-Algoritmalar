# Binary Search Tree Projesi

 [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


___

Binary Search Tree sağ ve sol olarak referans verilerek sağ tarafta x'ten büyük elemanlar, sol tarafta ise x'ten küçük elemanlar olacak şekilde ayırarak oluşturulur ve bu şekilde ilerler. Burada 
x sayısına root denir ve root'u bu dizi için 7 seçiyoruz.

5 ve 8 rakamlarını yerleştiriyoruz. 5, 7'den küçük olduğu için sol tarafta 8 ise 7'den büyük olduğu için sağ tarafta yer alıyor. Daha sonra 5 için, 1 ve 6'yı aynı şekilde yerleştiriyoruz. Dizideki 8'den tek büyük sayı 9 olduğu için onu da 8'in altına uygun şekilde yerleştirdikten sonra 7'nin sağ tarafındaki kısmı ile bir işimiz kalmadı.

1 sayısından küçük olduğu için 0, 1'in altında ve solda; 3 ise 1'den büyük olduğu için sağ tarafa eklendi. 2 sayısı 1'den büyük, 3'ten küçüktür. Bu yüzden 3'ün sol tarafında yer aldı. 4 ise 3'ten büyük olduğu için sağ tarafta yerleştirip binary search tree'yi tamamlamış olduk. Sonuç aşağıdaki gibidir;



                                                    7
                                                  /   \ 
                                                5      8
                                              /   \     \
                                             1     6     9
                                            /  \
                                           0    3
                                               /  \
                                              2    4