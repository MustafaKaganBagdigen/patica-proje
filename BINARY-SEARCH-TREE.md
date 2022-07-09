
SORU 1) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

🡆 Binary Search Tree: elemanların büyüklüğüne göre sırayla sağa veya sola doğru dallanarak uzayan sıralama yöntemidir.
Root olarak belirlenmiş en tepede bulunan elemandan sonra tek tek dizi sıralamasına göre elemanlar taranır. Sonraki elemanlar roottan küçükse soluna,
büyükse sağına doğru ilerlenerek orada bulunan birimlerin (node) büyüklüğüne bakılır. Node'ların bitimine kadar bu işlem devam eder. Node'lar bittiğinde
taranan eleman son node'un büyüklüğüne göre sağında veya solunda yeni bir node olarak yazılır. Buna göre yukarıdaki dizinin binary search
tree aşamaları şu şekildedir:

Dizinin rootu 7 dir.

🡆 1.aşama olarak 2. elemana bakarız. 5, roottan küçük olduğu için soluna doğru bir dal olarak yazılır.

          7 (root)
        ⬋
       5
       
       
🡆 2.aşama olarak 3. elemana bakarız. 1, roottan küçük olduğu için soluna doğru gidilir. Solda bulunan "5" alt dalından (node) küçük olduğu için onun da soluna 
yeni bir dal yazılır.

          7 (root)
        ⬋
       5
      ⬋
     1
     
🡆 3.aşama olarak 4. elemana bakarız. 8, roottan büyük olduğu için sağına doğru bir dal olarak yazılır.

          7 (root)
        ⬋  ⬊
       5     8
      ⬋
     1                           
 
🡆 4.aşama olarak 5. elemana bakarız. 3, roottan küçük olduğu için soluna doğru gidilir. Aynı zamanda "5" alt dalından (node) küçük olduğu için onun da soluna gidilir
ancak 1 node'undan büyük olduğu için sağına yeni bir dal yazılır.

          7 (root)
        ⬋  ⬊
       5     8
      ⬋
     1
      ⬊
        3
        
🡆 5.aşama olarak 6. elemana bakarız. 6, roottan küçük olduğu için soluna gidilir. Ancak "5" node'ndan büyük olduğu için bu node'un sağına yeni bir dal 
olarak yazılır. 

          7 (root)
        ⬋  ⬊
       5     8
      ⬋⬊
     1   6
      ⬊
        3 
        
🡆 6.aşama olarak 7. elemana bakarız. 0, roottan küçük olduğu için soluna doğru gidilir. Sonraki "5" alt dalından (node) küçük olduğu için onun da soluna 
gidilir ve son olarak "1" node'undan da küçük olduğu için "1" node'unun soluna yeni bir dal olarak yazılır.
        
              7 (root)
            ⬋  ⬊
           5     8
          ⬋⬊     
         1   6      
        ⬋⬊
       0   3                                                                                       
 
 
🡆 7.aşama olarak 8. elemana bakarız. 9, roottan büyük olduğu için sağına bakarız. Sağında bulunan "8" node'undan da büyük olduğu için bu node'un sağına yeni
bir dal olarak yazılır.

          7 (root)
        ⬋  ⬊
       5     8
      ⬋⬊     ⬊
     1   6      9
    ⬋ ⬊
   0    3 

🡆 8.aşama olarak 9. elemana bakarız. 4, roottan küçük olduğu için soluna, "5" alt dalından (node) küçük olduğu için onun da soluna,"1" node'undan büyük olduğu sağına 
gidilir ve son olarak "3" node'undan büyük olduğu sağına yeni bir dal olarak yazılır

          7 (root)
        ⬋  ⬊
       5     8
      ⬋
     1
    ⬋ ⬊
   0    3
         ⬊
           4         

🡆 9.aşama olarak 10. elemana bakarız. 2, roottan küçük olduğu için soluna, "5" alt dalından (node) küçük olduğu için onun da soluna,"1" node'undan büyük olduğu sağına, 
"3" node'undan küçük olduğu için soluna yeni bir dal olarak yazılır. Son node'un da yazılmasıyla işlem tamamlanmış olur.

          7 (root)
        ⬋  ⬊
       5     8
      ⬋
     1                -------------🡺 Tamamlanmış son hali bu şekildedir.
    ⬋ ⬊
   0     3
       ⬋  ⬊
      2      4     

                                        
