# InsertionSort
[22,27,16,2,18,6] -> Insertion Sort
-----------------------------------------------------------
[22,27,16,2,18,6] 22 den sonrası | index[0] ve index[1] yi karşılaştırıyoruz. 
[22,27,16,2,18,6] 22,27 den sonrası | index[1] ve index[2] yi karşılaştırıyoruz. 
[22,16,27,2,18,6] 22,27 den sonrası |index[0] ve index[1] yi karşılaştırıyoruz. 
[16,22,27,2,18,6] 16,22,27 den sonrası |index[2] ve index[3] yi karşılaştırıyoruz.  
[16,22,2,27,18,6] 16,22,27 den sonrası |index[1] ve index[2] yi karşılaştırıyoruz. 
[16,2,22,27,18,6] 16,22,27 den sonrası |index[0] ve index[1] yi karşılaştırıyoruz. 
[2,16,22,27,18,6] 2,16,22,27 den sonrası |index[3] ve index[4] yi karşılaştırıyoruz. 
[2,16,22,18,27,6] 2,16,22,27 den sonrası |index[2] ve index[3] yi karşılaştırıyoruz. 
[2,16,18,22,27,6] 2,16,22,27 den sonrası |index[1] ve index[2] yi karşılaştırıyoruz. 
[2,16,18,22,27,6] 2,16,18,22,27 den sonrası |index[4] ve index[5] yi karşılaştırıyoruz. 
[2,16,18,22,6,27] 2,16,18,22,27 den sonrası |index[3] ve index[4] yi karşılaştırıyoruz. 
[2,16,18,6,22,27] 2,16,18,22,27 den sonrası |index[2] ve index[3] yi karşılaştırıyoruz. 
[2,16,6,18,22,27] 2,16,18,22,27 den sonrası |index[1] ve index[2] yi karşılaştırıyoruz. 
[2,6,16,18,22,27] 2,16,18,22,27 den sonrası |index[0] ve index[2] yi karşılaştırıyoruz. 
[2,6,16,18,22,27] : sonuç  1+2+3+3+5 = 14 karşılaştırma yapıldı.

2)Big-O Notation
 -Big O (n^2)


3)Time Complexity
-The average case time complexity of Insertion sort is O(n^2)
-The worst case time complexity of Insertion sort is O(n^2)
-The best case time complexity of Insertion sort is O(n) 


4)Which case for 18?
-18 is in the scope of the avarage case because it is in the middle of the array.

5)First 4 Insertion Sort steps of the [7, 3, 5, 8, 2, 9, 4, 15, 6]

0-[7, 3, 5, 8, 2, 9, 4, 15, 6] 7 den sonrasi index[0] ve index[1] yi karşılaştırıyoruz.
1-[3, 7, 5, 8, 2, 9, 4, 15, 6] 3,7 den sonrasi index[1] ve index[2] yi karşılaştırıyoruz.
2-[3, 5, 7, 8, 2, 9, 4, 15, 6] 3,7 den sonrasi index[0] ve index[1] yi karşılaştırıyoruz.
3-[3, 5, 7, 8, 2, 9, 4, 15, 6] 3,5,7 den sonrasi index[3] ve index[4] yi karşılaştırıyoruz.
4-[3, 5, 7, 8, 2, 9, 4, 15, 6] ...