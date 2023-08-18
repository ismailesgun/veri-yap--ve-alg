# Insertion Sort Projesi

Bu projede verilen dizileri insertion sort ve selection sort algoritmaları ile sıralayacağız

## Insertion Sort

**Sıralanacak Dizi:**  [22,27,16,2,18,6]  
**Aşamalar:**

1. [22|27,16,2,18,6]
2. [22,27|16,2,18,6]
3. [16,22,27|2,18,6]
4. [2,16,22,27|18,6]
5. [2,16,18,22,27|6]
6. [2,6,16,18,22,27]
Dizi sıralandı. :)

Big-O gösterimi: O(n^2)

18 sayısının Time Complexity durumu, 18 sayısı ortada olduğundan Average Case olarak ifade edilir.

-----
## Selection Sort
 
**Sıralanacak Dizi:**   [7,3,5,8,2,9,4,15,6]   
**Aşamalar:**

1. Mevcut dizinin en küçük elemanı: 2  
   Dizinin sıralanmış hali: [2,7,3,5,8,9,4,15,6] 
2. Mevcut dizinin sıralanmamış kısmının en küçük elemanı: 3  
   Dizinin sıralanmış hali: [2,3,7,5,8,9,4,15,6]
3. Mevcut dizinin sıralanmamış kısmının en küçük elemanı: 4 
   Dizinin sıralanmış hali: [2,3,4,7,5,8,9,15,6]
4. Mevcut dizinin sıralanmamış kısmının en küçük elemanı: 5
   Dizinin sıralanmış hali: [2,3,4,5,7,8,9,15,6]

[7,3,5,8,2,9,4,15,6] dizisinin Selction Sort algoritmasına göre ilk 4 adım yapılarak sıralanmış hali: [2,3,4,5,7,8,9,15,6]