# [GITHUB REPO](https://github.com/Er3nairus/Merge-Sort-.git)

## [16,21,11,8,12,22] Dizisini merge sort tekniği ile sıralamak için ilk önce diziyi parçalara bölmeliyiz

### [16,21,11] [8,12,22] Şeklinde

bu parçaları da kendi içerisinde parçalayıp sıralamamızın ardından yeniden birleştirdiğimizde işlemimiz tamamlanacak

### [16] , [21,11]    ----    [8] , [12,22]
### [16] , [21] , [11]  ----  [8] , [12] , [22]
### [16] , [11,21]  ----  [8] , [12,22]
### [11,16,21]  ----  [8,12,22]
## [8,11,12,16,21,22]

Sıralamamızın Big O Notation'ı ise O(nlogn)
