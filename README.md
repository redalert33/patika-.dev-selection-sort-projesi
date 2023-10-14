# patika-.dev-selection-sort-projesi

Proje 1:

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1.Aşama: [2,27,16,22,18,6]
2.Aşama: [2,6,16,22,18,27]
3.Aşama  [2,6,16,22,18,27]
4.Aşama: [2,6,16,18,22,27]
5.Aşama: [2,6,16,18,22,27]

Big-O gösterimini yazınız.

O(n²)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

18 sayısı Average case'ye girer.(Aradığımız sayının ortada olması.)

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. Adım= [2,3,5,8,7,9,4,15,6] (2 ve 7 yer değiştirdi)
2. Adım= [2,3,5,8,7,9,4,15,6]
3. Adım= [2,3,4,8,7,9,5,15,6] (4 ve 5 yer değiştirdi)
4. Adım= [2,3,4,5,7,9,8,15,6] (5 ve 8 yer değiştirdi)
-----------------------------------------------------------------------------------------------------------------
# patika-.dev-merge-sort

Proje 2:

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16][21][11]-----------------------[8][12][22]

[16][21]---[11] ----------------------[8][12]---[22]

[16]- [21] - [11] ----------------------[8] - [12] - [22]
                    
[11][16][21]-------------------------[8][12][22]
              [8,11,12,16,21,22]

Big-O gösterimini yazınız.
merge sort için her zaman O(nlogn)

--------------------------------------------------------------------------------------------------------------------
# patika-.dev-binary-search-tree

Proje 3:

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

root =6
       6                   root 6 olduğu için:
    /      \               7>6 (7 sağa)
 1  5      7  8            5<6 (5 sola)
  \       /                1<5 (1 sola) 
   3      6                8>7 (8 sağa) 
  / \    /  \              3>1 (3 sağa)
0    4   2   9             6<7 (6 sola)
                           0<3 (0 sola)
                           9>6 (9 sağa)
                           4>3 (4 sağa)
                           2<6 (2 sola)
  
