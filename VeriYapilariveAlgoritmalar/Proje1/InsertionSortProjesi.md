```text
[22,27,16,2,18,6] -> Insertion Sort
```
`Soru1:` Yukarı verilen dizinin sort türüne göre aşamalarıaşamalarını yazınız.
```text
- First Pass -> [22, | 27, 16, 2, 18, 6]
- Second Pass -> [22, 27, | 16, 2, 18, 6]
- Third Pass -> [16, 22, 27, | 2, 18, 6]
- Fourth Pass -> [2, 16, 22, 27, | 18, 6]
- Fifth Pass -> [2, 16, 18, 22, 27, | 6]
- Final Array -> [2, 6, 16, 18, 22, 27]
```
`Soru2:`Big-O gösterimini yazınız.
```text
sum = (n*(n-1))/2 -> (n^2-n)/2 -> O(n^2)
```
`Soru3:`Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
```text
Time Complexity:
Average case: Aradığımız sayının ortada olması.
Worst case: Aradığımız sayının sonda olması.
Best case: Aradığımız sayının dizinin en başında olması.
```
```text
Average case
```
`Soru4:`[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı
```text
- min=2 -> swap 7 and 2 -> [2, | 3, 5, 8, 7, 9, 4, 15, 6]
- min=3 -> no need to swap [2, 3, | 5, 8, 7, 9, 4, 15, 6]
- min=4 -> swap 5 and 4 -> [2, 3, 4, | 8, 7, 9, 5, 15, 6]
- min=5 -> swap 8 and 5 -> [2, 3, 4, 5, | 7, 9, 8, 15, 6]
```
