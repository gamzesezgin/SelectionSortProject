# Selection Sort Project

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

Big-O gösterimini yazınız.

n+(n-1)+(n-2)+(n-3)+(n-4)+1 = n(n+1)/2  Big-o = n^2

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.

Aranan sayı 18, dizinin ortasındadır, 'Average case'

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[2,3,5,7,8,9,4,15,6]
[2,3,4,5,7,8,9,15,6]