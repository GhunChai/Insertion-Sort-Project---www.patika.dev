# Insertion-Sort-Project---www.patika.dev
[Patika.dev](https://www.patika.dev/tr)

[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Aşama 1 [22,27,16,2,18,6] 22 sayısı 27'den küçük olduğundan sayılar yerinde kalır.
Aşama 2 [16,22,27,2,18,6] 16 sayısı solundaki iki sayıdan küçük olduğundan kopyalanır ve solundaki iki sayı sağa kayarak boş bir yer açar 16 oraya yerleştirilir. 
Aşama 3 [2,16,22,27,18,6] yukarıda belirtilen mantık ile 2 en sola yerleşir solundaki sayılar 1 basamak sağa kayar
Aşama 4 [2,16,18,22,27,6]
Aşama 5 [2,6,16,18,22,27] insretion sort tamamlandı

2- Big-O gösterimini yazınız. 

Worst case n! =n*(n+1)/2 = (n^2+n)/2 = O(n^2)

3-Time Complexity:Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizi sıralandıktan sonra  [2,6,16,18,22,27] 18 ortada olacağından Average case olur

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[3,7,5,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[2,3,5,7,8,9,4,15,6]

[2,3,4,5,7,8,9,15,6]

www.patika.dev Marmara Uni hidden path insertion project.
