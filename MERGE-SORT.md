https://app.patika.dev/mustafakagan

[16,21,11,8,12,22] -> Merge Sort

**SORU 1)** Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

****⇨****  Merge sortta dizi sürekli şekilde ikiye bölünerek parçalara ayrılır. Bu işlem en küçük birime ulaşıncaya kadar devam eder.
Ayırma işlemi tamamlandıktan sonra birleştirme işlemine geçilir. Birleştirme işlemi ayırma sırasına göre yapılır. Her birleştirme işleminde küçük olan eleman kendi biriminde sırasını alarak sıralanır.
Buna göre yukarıda verilen dizinin sort türüne göre aşamaları şu şekilde olacaktır:



                  [16,21,11,8,12,22]                  
                  ⬋                ⬊                 
            [16,21,11]              [8,12,22]
            ⬋     ⬊               ⬋      ⬊
       [16,21]      [11]        [8]        [12,22]
        ⬋ ⬊         ↓          ↓           ⬋ ⬊
     [16]  [21]    [11]        [8]        [12]  [22]  -----🡺 En küçük birime kadar ayırma işlemi tamamlanmıştır.
        ⬊ ⬋         ↓          ↓           ⬊  ⬋             Birleştirme işlemine geçilmiştir.
      [16,21]      [11]       [8]          [12,22]             
         ⬊         ⬋           ⬊            ⬋                
           [11,16,21]              [8,12,22]                         
                  ⬊                ⬋           
                   [8,11,12,16,21,22]                -----🡺 Birleştirmeli sıralama sonucu dizinin son hali bu şekildedir.
                                                               

**SORU 2)** Big-O gösterimini yazınız.

****⇨**** Her basamağı ayrı işlem düşündüğümüzde ayırma ve birleştirme işleminde toplamda 6 tane (dizi eleman sayısı kadar) işlem yapılmıştır. Bu durumda dizinin
uzunluğu kadar işlem yapıldığından Big-O gösterimi: O(nlogn) şeklindedir.
