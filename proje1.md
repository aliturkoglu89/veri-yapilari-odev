Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Sol: En kucuk elemani secer ve en basa yazdiktan sonra son elemana kadar devam eder.
1-[2,27,16,22,18,6]
2-[2,6,16,22,18,27]
3-[2,6,16,22,18,27] --> 16 olmasi gerektigi biri    sirada oldugu iv=cin islem yapmadan sonraki adaima gecilir.
4-[2,6,16,18,22,27]
5-[2,6,16,18,22,27] --> 22 ve 27 sirali oldugundan tekrar islem yapilmadan sonuclandirilir.

Big-O gösterimini yazınız.

n tane elemanli kumeyi, 1 eleman kalana dek kontrol etmis oldugumuz icin, n+(n-1)+(n-2)...1 den n(n+1)/2=(n^2+n)/2 nin 
Big-O=n^2 dir.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Sol: Siralanmis dizilim:
[2,6,16,18,22,27], 18 sayisi ortada bulundugu icin average case kapsamindadir.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
Sol:
1-[2,3,5,8,7,9,4,15,6]
2-[2,3,5,8,7,9,4,15,6]
3-[2,3,4,8,7,9,5,15,6]
4-[2,3,4,5,7,9,8,15,6]

https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje