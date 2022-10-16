# [22,27,16,2,18,6] -> Insertion Sort

- ##### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  - Teker teker listeyi gezip en küçük değeri bulup birinci indise yerleştirir ve bunu tekrar eder
  - - [2,27,16,22,18,6] -> 22 ile 2 yer değiştirir.
    - [2,6,16,22,18,27] -> 27 ile 6 yer değiştirir.
    - [2,6,16,18,22,27] -> 22 ile 18 yer değiştirir.

- ##### Big-O gösterimini yazınız.
  - [2,27,16,22,18,6] n
    [2,6,16,22,18,27] n-1
    [2,6,16,18,22,27] n-2...
  - Şeklinde gittiği için O(n^2)'dir
  
- ##### Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

- ##### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
  - 18 sayısı başta veya sonra olmadığı için average case kapsamına girer.


