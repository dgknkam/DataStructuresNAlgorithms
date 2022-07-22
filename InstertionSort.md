[22,27,16,2,18,6] -> Insertion Sort 

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[2|,27,16,22,18,6] n-1

[2,6|,16,22,18,27] n-2

[2,6,16|,18,22,27] n-2


2) Big-O gösterimini yazınız.
   O(n)

3) Time Complexity: Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması,
Best case: Aradığımız sayının dizinin en başında olması.


    Avarage Case durumu= [22,27,16,2,18,6]
    
    Best Case durumu = [2,27,16,22,18,6]
    
    Worst Case durumu = [22,27,16,18,6,2]

4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[2,6,16,18,22,27] 18 sayısı dizinin ortanca değeridir Avarege Case kuralı olur. 

5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    

    1.Adım: [2,7,3,5,8,9,4,15,6]
    2.Adım: [2,3,7,5,8,9,4,15,6]
    3.Adım: [2,3,4,7,5,8,9,15,6]
    4.Adım: [2,3,4,5,7,8,9,15,6]