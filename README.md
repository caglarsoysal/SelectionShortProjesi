# SelectionShortProjesi
Insertion Sort:

Dizinin ilk elemanı (22) zaten sıralı bir şekilde kabul edilerek dizinin sıralanmış kısmı olarak işaretlenir.

İkinci eleman (27) dizinin sıralanmış kısmına eklenir ve karşılaştırılarak doğru sıralama yapılır. Bu durumda, 27 > 22 olduğundan 27'nin yerine 22 yerleştirilir ve 22, 27 dizisinin sıralanmış kısmı olarak işaretlenir.

Üçüncü eleman (16) dizinin sıralanmış kısmına eklenir ve karşılaştırılarak doğru sıralama yapılır. Bu durumda, 16 < 27 olduğundan 16, 27'nin soluna yerleştirilir ve 16, 22, 27 dizisinin sıralanmış kısmı olarak işaretlenir.

Dördüncü eleman (2) dizinin sıralanmış kısmına eklenir ve karşılaştırılarak doğru sıralama yapılır. Bu durumda, 2 < 16 olduğundan 2, 16'nın soluna yerleştirilir ve 2, 16, 22, 27 dizisinin sıralanmış kısmı olarak işaretlenir.

Beşinci eleman (18) dizinin sıralanmış kısmına eklenir ve karşılaştırılarak doğru sıralama yapılır. Bu durumda, 18 < 27 olduğundan 18, 27'nin soluna yerleştirilir ve 2, 16, 18, 22, 27 dizisinin sıralanmış kısmı olarak işaretlenir.

Altıncı eleman (6) dizinin sıralanmış kısmına eklenir ve karşılaştırılarak doğru sıralama yapılır. Bu durumda, 6 < 18 olduğundan 6, 18'in soluna yerleştirilir ve 2, 6, 16, 18, 22, 27 dizisinin sıralanmış kısmı olarak işaretlenir.

Big-O gösterimi: O(n^2)


18 sayısı, dizi sıralandıktan sonra en az 3 adımda bir değişiklik yapılması gereken bir sayıdır. Bu nedenle, 18 sayısı worst case senaryosuna girer.

18 sayısı average case kapsamına girer.

Insertion Sort’un time complexity’si :

Best Case : O(n)
Worst Case : O(n²)
Average Case : O(n²)



Selection Sort:

Dizinin en küçük elemanı (2) bulunur ve dizinin ilk elemanı ile yer değiştirilir. Dizi şu şekilde görünür: [2,3,5,8,7,9,4,15,6]

Dizinin ikinci en küçük elemanı (3) bulunur ve dizinin ikinci elemanı ile yer değiştirilir. Dizi şu şekilde görünür: [2,3,5,8,7,9,4,15,6]

Dizinin üçüncü en küçük elemanı (4) bulunur ve dizinin üçüncü elemanı ile yer değiştirilir. Dizi şu şekilde görünür: [2,3,4,8,7,9,5,15,6]

Dizinin dördüncü en küçük elemanı (5) bulunur ve dizinin dördüncü elemanı ile yer değiştirilir. Dizi şu şekilde görünür: [2,3,4,5,7,9,8,15,6]

##patika.dev ödevidir
