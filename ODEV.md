# Proje 1

#### Insertion Sort

0. Asama  [22, 27, 16, 2, 18, 6]
1. Asama  [16, 22, 27, 2, 18, 6] ### 22 , 27'den kucuk oldugu icin yer degismez. 16 , 22'den kucuk oldugu icin ilk basta olacak.
2. Asama  [2, 16, 22, 27, 18, 6] ## 2 , 16'den kucuk oldugu icin ilk basta olacak.
3. Asama  [2, 16, 18, 22, 27, 6] ## 18 , 22'den kucuk oldugu icin ondan once olacak.
4. Asama  [2, 6, 16, 18, 22, 27]  

Big-O = O(n)


##### Selection Sort  ############
#### En kucugunu belirliyoruz onu ilk koyuroruz ondan sonra ilk kullanmadan en kucuk onun yaninda koyuyoruz boyle bitene kadar.
0. Asama   [22, 27, 16, 2, 18, 6]
1. Asama   [2, 22, 27, 16, 18, 6]
2. Asama   [2, 6, 22, 27, 16, 18]
3. Asama   [2, 6, 16, 18, 22, 27]


<!-- ###### Merge ########
#### ortadan ikiye bolerek tek numara ulasana dek enkucuk ile siramaya baslayarak sirayacagiz.

0. Asama   [22,  27,  16,  2,  18,  6]
                              
1. Asama                [22, 27, 16]                                [2, 18, 6]
                       /          \                                 /        \
2. Asama              [22, 27]  [16 ]                             [2, 18]  [ 6 ]
                      /    \       \                             /     \      \
3. Asama            [22 ]  [27 ]    [ 16]                        [2 ] [ 18]  [ 6 ]
                     \     /       /                             /     /      /
4. Asama            [22, 27] [ 16]                              [2, 18]   [ 6]
                      
5. Asama            [16, 22, 27]                              [2 , 18, 6]
6. Asama        [2, 6, 16, 18, 22, 27] -->



#### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.     

Bun larin arasina En worst case' girer Cunku enson indexing yanida oldugu icin Tum value'yu bakmamiz lazim




### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. 



1. Asama [2, 7, 3, 5, 8, 9, 4, 15, 6]
2. Asama [2, 3, 7, 5, 8, 9, 4, 15, 6]
3. Asama [2, 3, 4, 7, 5, 8, 9, 15, 6]
4. Asama [2, 3, 4, 5, 7, 8, 9, 15, 6]
