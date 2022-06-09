# algoritma_ve_veri_yapilari

<!-- Patika, Veri Yapıları ve Algoritma Dersi Proje-1 -->

1) [22,27,16,2,18,6] -> Insertion Sort

    a) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

<!-- Patika eğitim videosunda verilen "Insertion Sort" dersine göre aşamalar yazılmıştır-->

      [22,27,16,2,18,6] --- n
      [2,27,16,22,18,6] --- (n-1)
      [2,6,16,22,18,27] --- (n-2)
      [2,6,16,18,22,27] --- (n-3)
      [2,6,16,18,22,27] --- 1



    b) Big-O gösterimini yazınız.

    Big-O gösterimi= O(n^2)

    c) Time Complexity: 
    
    Average Case: Aradığımız sayının ortada olması - Aradığımız sayının 16 veya 18 olma durumu.
    Worst Case: Aradığımız sayının sonda olması - Aradığımız sayının 27 olma durumu
    Best Case: Aradığımız sayının dizinin en başında olması. - Aradığımız sayının 2 olma durumu

    d) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

         - Dizi sıralandıktan sonra 18 sayısı dizinin ortasına gelmektedir. Dolayısıyla "Average Case" kapsamına girer.

  2)  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

  <!-- Patika eğitim videosunda verilen "Insertion Sort" dersine göre aşamalar yazılmıştır-->

    - [2,3,5,8,7,9,4,15,6] -- (1)
    - [2,3,5,8,7,9,4,15,6] -- (2)
    - [2,3,4,8,7,9,5,15,6] -- (3)
    - [2,3,4,5,7,9,8,15,6] -- (4)