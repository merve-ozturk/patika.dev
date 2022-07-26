Proje-3 Binary Search Tree 

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

Binary-Search-Tree aşamaları:

Root 7’dir. 5, 7'den küçük olduğundan root'un solunda bulunur.

        7
       /
      5

1, 7 ve 5'ten küçük olduğundan 5'in solunda bulunur.

        7
       /
      5
     /
    1

8, 7'den büyük olduğundan root'un sağında bulunur.

        7
       / \
      5   8
     /
    1

3, 7 ve 5'ten küçük 1'den büyük olduğundan 1'in sağında bulunur.

        7
       / \
      5   8
     /
    1
     \
      3

6, 7'den küçük 5'ten büyük olduğundan 5'in sağında bulunur.

        7
       / \
      5   8
     / \
    1   6
     \
      3

0; 7,5 ve 1'den küçük olduğundan 1'in solunda bulunur.

        7
       / \
      5   8
     / \
    1   6
   / \
  0   3

9, 7 ve 8'den büyük olduğundan 8'in sağında bulunur.

        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3

4, 7 ve 5'ten küçük 1 ve 3'ten büyük olduğundan 3'ün sağında bulunur.

        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
       \
        4

2,7 ve 5'ten küçük 1'den büyük ve 3'ten küçük olduğundan 3'ün soluna yazılır.

        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
     / \
    2   4



     



    
        

