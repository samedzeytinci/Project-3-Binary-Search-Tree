# Project-3-Binary-Search-Tree
[7,5,1,8,3,6,0,9,4,2] Binary Search Tree

[0,1,2,3,4,5,6,7,8,9] Büyükten küçüğe sıralayıp orta elemanı root olarak seçiyorum.
1-                                      [7]
2-                  [5]                                 [8]
3-          [1]                 [6]                          [9]
4-  [0]           [3]
5-              [2]  [4]


İlk eleman 7'yi root olarak alırız.
İkinci eleman 5, root'tan küçük olduğu için sol çocuk olur.
Üçüncü eleman 1, 5'ten küçük olduğu için 5'in sol çocuğu olur.
Dördüncü eleman 8, root'tan büyük olduğu için sağ çocuk olur.
Beşinci eleman 3, 1'den büyük ama 5'ten küçük olduğu için 1'in sağ çocuğu olur.
Altıncı eleman 6, 5'ten büyük ama 7'den küçük olduğu için 5'in sağ çocuğu olur.
Yedinci eleman 0, 1'den küçük olduğu için 1'in sol çocuğu olur.
Sekizinci eleman 9, root'tan ve 8'den büyük olduğu için 8'in sağ çocuğu olur.
Dokuzuncu eleman 4, 3'ten büyük ama 5'ten küçük olduğu için 3'ün sağ çocuğu olur.
Onuncu eleman 2, 1'den büyük ama 3'ten küçük olduğu için 3'ün sol çocuğu olur.
