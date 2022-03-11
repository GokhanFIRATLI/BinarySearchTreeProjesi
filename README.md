# BinarySearchTreeProjesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

root=7,

 - 5, 7'den küçük olduğu için 7'nin solunda bulunur.
 - 1, 7'den küçük olduğu için 7'nin solunda bulunur ve 1, 5'ten küçük oluğu için 5'in solunda bulunur.
 - 8, 7'den büyük olduğu için 7'nin sağında bulunur.
 - 3, 7'den küçük olduğu için 7'nin solunda bulunur; 3, 5'ten küçük olduğu için 5'in solunda bulunur ve 3, 1'den büyük olduğu için 1'in sağında bulunur.
 - 6, 7'den küçük olduğu için 7'nin solunda bulunur ve 6, 5'ten büyük olduğu için 5'in sağında bulunur.
 - 0, 7'den küçük olduğu için 7'nin solunda bulunur; 0, 5'ten küçük olduğu için 5'in solunda bulunur ve 0, 1'den küçük olduğu için 1'in solunda bulunur.
 - 9, 7'den büyük olduğu için 7'nin sağında bulunur ve 9, 8'den büyük olduğu için 8'in sağında bulunur.
 - 4, 7'den küçük olduğu için 7'nin solunda bulunur; 4, 5'ten küçük olduğu için 5'in solunda bulunur; 4, 1'den büyük olduğu için 1'in sağında bulunur ve 4, 3'ten büyük olduğu için 3'ün sağında bulunur.
 - 2, 7'den küçük olduğu için 7'nin solunda bulunur; 2, 5'ten küçük olduğu için 5'in solunda bulunur; 2, 1'den büyük olduğu için 1'in sağında bulunur ve 2, 3'ten küçük olduğu için 3'ün solunda bulunur.

```
         7
       ↙  ↘
      5     8
    ↙  ↘     ↘
   1     6     9
 ↙  ↘
0     3
    ↙  ↘
  2      4
```
