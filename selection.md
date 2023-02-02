# {Selection Sort Projesi}

### [22,27,16,2,18,6] - Insertion Sort

soldan başlayıp artarak ilerle ve sıralama yap.

1. adım : 22 | 27 16 2 18 6
2. adım : 22 27 | 16 2 18 6 
3. adım : 16 22 27 | 2 18 6
4. adım : 2 16 22 27 | 18 6
5. adım : 2 16 18 22 27 | 6

son adım : 2 6 16 18 22 27

### Big-O Notation:

O(n^2^) dir. 

### Time-Complexity: 

18 sayısı dizinin ortasında olduğundan *average case*'dir.

### [7,3,5,8,2,9,4,15,6] - Selection Sort 
(ilk dört adım)

önce dizideki minimum değeri bul (daha küçüğü var mı diye bak ve yerlerini değiştir) ve sırala.

1. adım : [2] 3 5 8 7 9 4 15 6
2. adım : [2 3] 5 8 7 9 4 15 6
3. adım : [2 3 4] 8 7 9 5 15 6
4. adım : [2 3 4 5] 7 9 8 15 6