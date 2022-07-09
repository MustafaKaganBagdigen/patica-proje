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

**⇨** Avarage case= O(n^2)
**⇨** Worst case= O(n^2)
**⇨** Best case= O(n^2)

**SORU 4)** Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

**⇨** Dizi selection sorta göre sıralandıktan sonra son hali [2,6,16,18,22,27] şeklinde olacaktır. 
Bu durumda aradığımız 18 sayısı **avarage case** kapsamına girmektedir.
