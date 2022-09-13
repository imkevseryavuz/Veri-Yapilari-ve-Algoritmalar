## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1. İlk eleman 7 yi seçelim.
2. 5 sayısı 7 den küçük olduğundan 7 nin soluna eklendi.
3. 1 sayısı 5 ten ve 7 den küçük olduğu için 7 ve 5 in soluna eklendi.
4. 8 sayısı 7 den büyük olduğu için 7 nin sağına eklendi.
5. 3 sayısı 7 den ve 5 ten küçük olduğu için 5 in soluna 1 in sağına eklendi.
6. 6 sayısı 7 den küçük olduğu için 7 nin soluna, 5 ten büyük olduğu 5 iniçin sağına eklendi.
7. 0 sayısı 7,5 ve 1 den küçük olduğu için 1 in soluna eklendi.
8. 9 sayısı 7 den ve 8 den büyük olduğu için 8 in sağına eklendi.
9. 4 sayısı 7 den ve 5 ten küçük olduğu için 5 in soluna 1 ve 3 ten büyük olduğu için 3 ün sağına eklendi.
10. 2 sayısı 7 den ve 5 ten küçük olduğu için 5 in soluna,1 den büyük olduğu için sağına, 3 ten küçük olduğu için 3 ün soluna eklendi.

                 7
                / \
               5   8
             /  \   \
            1    6   9
           / \
           0  3
              /\
             2  4