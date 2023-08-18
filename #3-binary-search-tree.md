# Binary Search Tree Projesi

Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]  
Dizi ağaç yapısına en baştaki elemandan eklenmeye başlanacaktır.
1. Kök: 7. Solunda 5, Sağında 8 bulunur
2. 5'in sağına  6, soluna 1 gelir
3. Dizide 6'dan büyük olan elemanlar kök ve kökün sağ yaprağından bulunucağından6'ın child node'u bulunmaz
4. Dizide 1 node'undan sonra bulunan küçük 0 sol child node'a 1'den büyük olan 3 değeri ise sol child node'a yerleştirilir
5. 0 bu dizin en küçük elemanıdır o yüzden child nodeu bulunmaz
6. 3 nodeundan küçük 2 elamanı sağ child node'a yerleşir

7. Kalan eleman 9 hem 7'den büyük hem de 8'den büyük olduundan 8 node'unun sol child node'una yazılır.
