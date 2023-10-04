# Merge

 [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Merge sort algoritması, bir diziyi sıralamak için "böl ve birleştir" (divide and conquer) stratejisini kullanan bir sıralama algoritmasıdır. İşte verilen dizinin merge sort algoritması ile sıralanma aşamaları:

# [16, 21, 11] [8, 12, 22]: Diziyi iki eşit parçaya böl.
[16] [21, 11] [8] [12, 22]: Her parçayı tek elemana kadar böl.
[16] [21] [11] [8] [12] [22]: Şimdi her eleman ayrı bir parça olarak kabul ediliyor.
[16, 21] [8, 11] [12, 22]: Parçaları sıralayarak birleştir. (Bu adımda "merge" işlemi gerçekleşir)
[8, 11, 16, 21] [12, 22]: İki parçayı birleştirerek sıralı bir dizi elde edilir.
[8, 11, 12, 16, 21, 22]: Son olarak, iki sıralı parçayı birleştirerek tam sıralı diziyi elde edersiniz.
Bu aşamalar sonucunda verilen dizi, merge sort algoritması ile sıralanmış olur.

Big-O Notasyonu:

# Merge sort algoritmasının zaman karmaşıklığı O(n log n)’dir. Burada "n" dizinin eleman sayısını temsil eder. Merge sort, her zaman logaritmik zaman karmaşıklığına sahiptir çünkü her seviyede n eleman bölünür ve her seviyede en fazla n işlem yapılır. Bu özellik, merge sort'u büyük veri setlerinde etkili bir şekilde kullanılabilir kılar.
