# InsertionSortProject



## [22,27,16,2,18,6] -> Insertion Sort aşaması

  [**2**,27,16,**22**,18,6] -> listenin 0. indeksi ile 3. indeksi yer değiştirir.
  [2,**6**,16,22,18,**27**] -> listenin 1. indeksi ile 5. indeksi yer değiştirir.
  [2,6,16,22,18,27] -> listenin 2. indeksi ile herhangi bir indeks yer değiştirmez.
  [2,6,16,**18**,**22**,27] -> listenin 3. indeksi ile 4. indeksi yer değiştirir.
  [2,6,16,18,22,27] -> listenin 4. indeksi ile herhangi bir indeks yer değiştirmez.



## Big-O Gösterimi

  6 elemanlı bu listedeki sort işlemi için ilk olarak en küçük eleman bulunmalı. Bu nedenle eleman sayısı kadar karşılaştırma yaparak en küçük eleman bulunuyor. 
  En küçük eleman 0. indekse yazıldıktan sonra 1. indeks için kalan en küçük eleman aranıyor. Bunun için de eleman sayısının bir eksiği kadar karşılaştırma yapılarak ikinci en küçük eleman bulunuyor. 
  Bu işlemler en sona kadar devam ediyor.
  Bu algoritmada yapılan işlem sayısı -> **n + n - 1 + n -2 + .... + 1** 
  Bunu işlem sayısının genel denklemi -> **n*(n+1)/2** şeklinde yazılabilir.
  Big-0 gösterimi için de en yüksek üst olan **n<sup>2<sup>** ifadesi alınır. 
  Böylelikle **O(n<sup>2<sup>)** olarak gösterilir.
  


## 18 sayısı hangi case kapsamına girer?
  
  Dizi sıralandıktan sonra 18 sayısı dizinin ortalarında bulunduğu için **Average case** kapsamına girer. 

  
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
  
  1 -> [**2**,3,5,8,**7**,9,4,15,6] --> dizideki 2 elemanı ile 7 elemanı yer değiştirir.
  2 -> [2,**3**,5,8,7,9,4,15,6] --> dizideki 3 elemanı ikinci en küçük eleman olduğu için yerinde kalır.
  3 -> [2,3,**4**,8,7,9,**5**,15,6] --> dizideki 4 elemanı ile 5 elemanı yer değiştirir.
  4 -> [2,3,4,**5**,7,9,**8**,15,6] --> dizideki 5 elemanı ile 8 elemanı yer değiştirir.
