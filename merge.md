Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


0. Asama [16,21,11,8,12,22]

1. Asama    [16,21,11]      [8,12,22]          n/2
               ||              ||
2. Asama  [16,21] [11]      [8,12] [22]       n/4
               ||                 ||
3. Asama  [16] [21] [11]    [8] [12] [22]     n/6
                ||                ||
4. Asama  [16,21] [11]      [8,12] [22]       
                ||              ||
5. Asama  [11,16,21]        [8,12,22]
                \\            //
6. Asama       [8,11,12,16,21,22]

Big-O  = O(nlogn)

