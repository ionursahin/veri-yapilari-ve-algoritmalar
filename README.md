# Veri Yapıları ve Algoritmalar
## Insertion Sort, Merge Sort ve Binary Search Tree Ödevi
### Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[2,27,16,22,18,6] [2,6,16,22,18,27] [2,6,16,18,22,27]
2.Big-O gösterimini yazınız.
O(n²)=O(6²)
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
[Average_Case]
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[Average_Case]

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1.Adım: [2,3,5,8,7,9,4,15,6] 
2.Adım: [2,3,4,8,7,9,5,15,6] 
3.Adım: [2,3,4,5,7,9,8,15,6] 
4.Adım: [2,3,4,5,6,9,8,15,7]

### Merge Sort
[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.

1.1
````
[16] [21,11]
[16] [21] [11]
[16] [11,21]
[11,16,21]
````
1.2
````
[8] [12,22]
[8] [12] [22]
[8] [12,22]
[8,12,22]
````
1.3 
````
[8,11,12,16,21,22]
````
2- O(nlogn)
### Binary Search Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1-Bu dizide ilk elemanı root olarak seçiyoruz. 2-Sonrasında gelen elemanları aşağı doğru şekilde küçükse sola büyükse sağa şeklinde yazıyoruz.

                        7
                     /     \
                    5       8
                   /\         \
                  1  6         9
                 / \  
                0   3
                   / \
                  2   4

[Patika Profilim](https://app.patika.dev/cias)