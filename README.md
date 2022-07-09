*Bilgilendirme: Insertion sort videosunda gösterilenin aslında selection sort olması sebebiyle projemizde insertion sort ve selection sort ayrı ayrı gösterilmiştir.

SELECTION SORT PROJESI
----------------------
[22,27,16,2,18,6] 

**SORU 1)** Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

**⇨** Selection sort'a göre:

Dizedeki ilk sıradaki eleman, sırayla tüm dizeyi tarar ve en küçük elemanlıyla yer değiştirir. Bu işlem bittikten sonra sırasıyla sonuncu elemana kadar bu işlem devam eder. Bu şekliyle yukarıdaki dizenin aşamaları sırasıyla şu şekilde devam eder:

**⇨** [22,27,16,2,18,6]
**⇨** [2,27,16,22,18,6] 
**⇨** [2,6,16,22,18,27] 
**⇨** [2,6,16,22,18,27]
**⇨** [2,6,16,18,22,27]
**⇨** [2,6,16,18,22,27]

**SORU 2)** Big-O gösterimini yazınız.

**⇨** O(n^2)

**SORU 3)** Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

**⇨** Avarage case= 16 ve 18 = O(n^2) 
**⇨** Worst case= 27 = O(n^2)
**⇨** Best case= O(n^2)

**SORU 4)** Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

**⇨** Dizi selection sorta göre sıralandıktan sonra son hali [2,6,16,18,22,27] şeklinde olacaktır. 
Bu durumda aradığımız 18 sayısı **avarage case** kapsamına girmektedir.

**EKSTRA SORU )** [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

**⇨** [7,3,5,8,2,9,4,15,6]
**⇨** [2,3,5,8,7,9,4,15,6]
**⇨** [2,3,5,8,7,9,4,15,6]
**⇨** [2,3,4,8,7,9,5,15,6]

INSERTION SORT PROJESI
----------------------
[22,27,16,2,18,6] 

**SORU 1)** Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

**⇨** Insertion sort'a göre:

Dizedeki 2. sıradaki elemandan başlayarak sırasıyla her eleman kendinden önceki elemanları tarar ve kendinden önceki elemandan küçükse aradaki yerini bulur. Bu şekilde sırayla büyük elemanlar sağa doğru kaydırılır. Dikkat edilmesi gereken husus bu yapıldığı esnada her küçük eleman yalnızca kendinden öncekiyle yer değiştirmez kendinden önceki elemanlar arasında sıralı yerini alır ve diğer elemanlar sağa doğru kayarlar. Bu şekilde sıralama devam eder. Buna göre soruda verilen dize için insertion sort aşamaları şu şekildedir:

**⇨** [22,27,16,2,18,6]
**⇨** [16,22,27,2,18,6]
**⇨** [2,16,22,27,18,6]
**⇨** [2,16,18,22,27,6]
**⇨** [2,6,16,18,22,27]
**⇨** [2,6,16,18,22,27]


**SORU 2)** Big-O gösterimini yazınız.

**⇨** O(n^2)

**SORU 3)** Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

**⇨** Avarage case= O(n^2)
**⇨** Worst case= O(n^2)
**⇨** Best case= O(n)

**SORU 4)** Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

**⇨** Dizi insertion sorta göre sıralandıktan sonra son hali [2,6,16,18,22,27] şeklinde olacaktır. 
Bu durumda aradığımız 18 sayısı **avarage case** kapsamına girmektedir.

**EKSTRA SORU )** [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

**⇨** [3,7,5,8,2,9,4,15,6]
**⇨** [3,5,7,8,2,9,4,15,6]
**⇨** [3,5,7,8,2,9,4,15,6]
**⇨** [2,3,5,7,8,9,4,15,6]
