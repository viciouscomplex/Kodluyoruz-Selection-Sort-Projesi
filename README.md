# Kodluyoruz-Selection-Sort-Projesi

## [22,27,16,2,18,6] -> Insertion Sort

## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1.Adım: [22,27,16,2,18,6] İlk 2 eleman kıyaslanır ve küçük olan başa konur.

2.Adım: [16,22,27,2,18,6] 2.ve 3. eleman kıyaslanır ve eğer 3.eleman 2.elemandan küçük ise 1.elemanla da kıyaslanır ve konumlanır.

3.Adım: [2,16,22,27,18,6] 3.ve 4.eleman kıyaslanır ve eğer 4.eleman 3.elemandan küçük ise 2. elemanla da kıyaslanır. 2.elemandan da küçük ise 1.elemanla kıyaslanır ve konumlanır.

4.Adım: [2,16,18,22,27,6] 4.ve 5 eleman kıyaslanır ve eğer 5.eleman 4.elemandan küçük ise 3.elemanla da kıyaslanır. 3.elemandan da küçük 2.elemandan büyük olduğu için oraya konumlanır.

5.Adım: [2,6,16,18,22,27] 5.ve 6.eleman kıyaslanır ve eğer 6.eleman 5.elemandan küçük ise 4.elemanla kıyaslanır. 4.elemandan küçük ise 3. elemanla kıyaslanır. 3.elemandan küçük ise 2.elemanla da kıyaslanır. 2.elemandan küçük 1.elemandan büyük olduğu için oraya konumlanır.


## Big-O gösterimini yazınız.

--> O(n^2)

## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[2,6,16,18,22,27]

Aradığımız sayı ortada olduğu için Average case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1.Adım: [2,7,3,5,8,9,4,15,6] Dizinin en küçük elemanı olan 2'yi alır ve başa yerleştirir.

2.Adım: [2,3,7,5,8,9,4,15,6] Daha önce en başa koyulan 2 sayısı hariç geri kalan dizideki en küçük sayıyı bulur ve 2. elemana yerleştirir.

3.Adım: [2,3,4,7,5,8,9,15,6] Daha önce lk 2 sıraya koyulan 2 ve 3 'ü kenara bırakıp geri kalan dizideki en küçük sayıyı bulur ve 3. elemana yerleştirir.

4.Adım: [2,3,4,5,7,8,9,15,6] Daha önce iilk 3 sıraya koyulan 2,3 ve 4'ü kenara bırakıp geri kalan dizideki en küçük sayıyı bulur ve 4. elemana yerleştirir.
