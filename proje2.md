Merge Sort Projesi
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Sol: 
1-[16,21,11]    [8,12,22]
2-[16,21] [11]  [8,12] [22]
3-[16] [21] [11]    [8] [12] [22]
4-[11] [21] [16]    [8] [12] [22]
5-[11] [16] [21]    [8] [12] [22]
6- [11,16,21]   [8,12,22]
7- [8,11,12,16,21,22]

Big-O gösterimini yazınız.
Sol:
1-n kez kontrol ettigi icin O=(n),
2-tek eleman kalana kadar 2 ye boldugu icin O=(logn),

O=(nlogn)

https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje