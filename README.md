# Merge Sort Projesi

 ## [16,21,11,8,12,22] -> Merge Sort

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

### Sayılar tek basamaklı sayıya düşene kadar sağ ve sol olmak üzere iki tarafa ayrılır. Sonrasında bu sayılar küçükten büyüğe doğru sıralayarak dizinimizin doğru sıralamasını tamamlıyoruz



- [16,21,11,8,12,22]
- [16,21,11] ; [8,12,22] Sağ ve sol olmak üzere ikiye ayırdık.
- [16] [21,11]; [8,12];[22] 
- [16]; [21]; [11];[8];[12];[22] Tek sıraya geldik ve buradan sonra küçükleri sola büyükleri sağa alarak sıralamamıza devam edelim.
- [16]; [11,21];[8,12];[22]
- [11,16,21]; [8,12,22]
- [8,11,12,16,21,22] Sıralamamızı parça parça ayırdık ve adımların sonunda en küçükten büyüğe doğru sıraladık.

### Big-O gösterimini yazınız.

​      *2^x = n*

​      *x = logn*

​     *O(nlogn)* 

