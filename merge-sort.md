# Birleştirme Sıralaması Projesi

Bu projede Merge Sort yöntemini kullanarak verilen diziyi küçükten büyüğe sıraladım.

Başlangıç dizisi: [16, 21, 11, 8, 12, 22]

**Adım adım sıralama:**

1. Dizi ikiye ayrılır:
   [16, 21, 11] ve [8, 12, 22]

2. Tekrar parçalara ayrılır:
   [16] [21, 11] [8] [12, 22]

3. Küçük diziler sıralanır:
   [16] [11, 21] [8] [12, 22]

4. Diziler birleştirilir:
   [11, 16, 21] ve [8, 12, 22]

5. Sonuç:
   [8, 11, 12, 16, 21, 22]

**Big-O gösterimi:**

O(n log n)

Birleştirme sıralaması, diziyi sürekli ikiye bölerek sıralama yapar. Daha sonra parçaları tekrar birleştirir.
