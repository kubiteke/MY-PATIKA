1) [16,21,11,8,12,22] -> Merge Sort

    a - Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

<!-- Liste, elemanlar tek kalana kadar ayrılır -->

   - [16,21,11,8,12,22]
   - [16,21,11] & [8,12,22] 
   - [16] [21,11] & [8] [12,22]
   - [16] [21] [11] & [8] [12] [22]
<!-- Buradan sonra birleşmeye başlar -->
   - [16] [11,21] & [8] [12,22]
   - [11,16,21] & [8,12,22]
   - [8,11,12,16,21,22]
   


    b - Big-O gösterimini yazınız.

Merge Sort'ta Big-O gösterimi: O(nlogn) şeklindedir.

