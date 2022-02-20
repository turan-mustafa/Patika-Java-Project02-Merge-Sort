# Patika-Java-Project02-Merge-Sort

# Proje 2

## [16,21,11,8,12,22] -> Merge Sort

•	Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
•	Big-O gösterimini yazınız.



## YANIT:

[16,21,11,8,12,22] -> Merge Sort

## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 

- İlk olarak diziyi 2'ye bölüyoruz, sonra bölünen parçaları tekrar 2'ye bölüyoruz, tek eleman kaldığı için artık bölmüyoruz. 

[16,21,11,8,12,22]

[16,21,11] [8,12,22]

[16,21] [8,12]

[16] [21] [8] [12]

[11] [22]

[16] [21] [11] <-> [8] [12] [22]

İkili olarak bölme işlemi bittiğine göre şimdi tek tek birleştirme işlemine başlıyoruz.


- Sonra birleştirme adımına geçiyorum, elimizde 2'y bölümle oluşan küçük sıralı diziler yer alıyor. Bu dizilerin ilk değerlerinin en küçük olduğunu biliyoruz artık, ilk sayıları birbirleri ile karşılaştırarak küçükten büyüğe doğru ikili olarak sıralıyor ve sıralı bir bizi yazmaya başlıyoruz.

[16] [21] [11] <-> [8] [12] [22]

[16,21] [11] <-> [8,12] [22]

[16,21] [11] <-> [8,12] [22]

[11,16,21] <-> [8,12,22]

[8,11,12,16,21,22]


## • Big-O gösterimini yazınız.

O(nlogn)


