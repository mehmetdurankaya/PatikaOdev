Insertion Sort Projesi
Proje 1

[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Adım 1:Öncelikle dizinin bütünü incelenir ve en küçük olan sayı dizinin en solundaki ilk sayı ile yer değişir.
       [2,27,16,22,18,6] -> 2 ile 22 yer değiştirir.
Adım 2:Dizinin içindeki en küçük sayıyı soldan ilk sıraya yerleşmiştir İkinci sıra için de 2'den sonra gelen en küçük sayıyı arar ve ikinci sırada olan sayı ile yer değiştirir.
       [2,6,16,22,18,27] -> 6 ile 27 yer değiştiriyor.
Adım 3:[2,6,16,22,18,27] -> 3. sıradaki sayı sıralanmayan sayılar arasında en küçük olduğu için yer değiştirmez.
Adım 4:[2,6,16,18,22,27] -> 18 ile 22 yer değiştirir.
Adım 5:[2,6,16,18,22,27] -> 5. sıradaki sayı en sıralanmayan sayıları içinde en küçük olduğu için yer değiştirmez .
Adım 6:[2,6,16,18,22,27] -> 6. sıradaki sayı en büyük olur ve dizi, küçükten büyüğe sıralanmış olur.

Big-O gösterimini yazınız.

elaman sayısı 'n' olsun en küçük elemanı bulmak için 'n' kadar elemanı kontrol ederiz. Eleman sayısı kadar elaman kontrol edilir.
sonra geri kalan elemanlar kontrol edilir bu da 'n-1' dir. Yani bulunan elemanı toplam eleman sayısından çıkarır kalan elemanlar kontrol edilir.
bu şekilde bir döngü olarak devam eder ve 'n+(n-1)+(n-2)+(n-3)...'şeklinde ilerler. Yani 1'den n'e kadar olan sayıların toplamından (n.(n-1))/2 gelir buradan da Big-O Notation'umuz O(n²) o da O(36)'dır.

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Average Case: 16, 18
Worst Case: 27
Best Case: 2
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average Case
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
