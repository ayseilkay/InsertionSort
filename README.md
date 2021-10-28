  ## 1. InsertionSort aşamaları aşağıdaki gibidir.
   [22,27,16,2,18,6] 
-> [22,27,16,2,18,6]
-> [16,22,27,2,18,6]
-> [2,16,22,27,18,6]
-> [2,16,18,22,27,6]
-> [2,6,16,18,22,27]

 ## 2. Big-O gösterimi aşağıdaki gibidir.
    O(n²) dir. 
 
 ## 3.Time Complexityleri aşağıdaki gibidir. 
 * Best Case : O(n)-- en iyi durumda(dizi sıralıdır gibi dusunebiliriz )
 * Worst Case: O(n²) -- en kötü durumda ( dizi ters sıralanmıs gibi dusunebilir.)
 * Avereage Case: O(n²) --(genelde meydana gelen durum)

 ## 4. Dizi sıralandıktan sonra 18 sayısı average case kapsamına girmektedir. 

 ## 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
dizi=[7,3,5,8,2,9,4,15,6]
1->  [3,7,5,8,2,9,4,15,6]
2->  [3,5,7,8,2,9,4,15,6]
3->  [2,3,5,7,8,9,4,15,6]
4->  [2,3,4,5,7,8,9,15,6]