# mergesortproje
##https://patika.dev  Merge Sort Projesi
# Veri Yapıları ve Algoritmalar - Insertion Sort



## Proje:
1) **[16,21,11,8,12,22]** Dizisinin **Merge Sort**a göre aşamalarını yazınız.
- [16,21,11] **+** [8,12,22]
- [16] + [21,11] **+** [8] + [12,22]
- [16] + [11,21] **+** [8] + [12,22]
- [11,16,21] **+** [8,12,22]
-------------------------
- **[8,11,12,16,21,22]**
2) Big O Gösterimini yazınız.
- Dizi tek elemanlı olarak parçalanana kadar ikiye ayrılır. Ayrılan her dizide işlem için dizinin uzunluğu kadar olan n tane işlem yapıldığından = O(n*(logn)) => O(6*(log6)) olur
