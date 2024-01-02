# MergeSortProjesi
Kodluyoruz FrontEnd 101 Eğitiminde Merge Sort Proje Reposu

16,21,11,8,12,22 – Birinci aşama: Dizi ortadan ikiye bölünür.

16,21,11	8,12,22 – İkinci aşama: Elde edilen diziler ortadan ikiye bölünür.

16,21		11		8,12		22 – Üçüncü aşama: Tek eleman kalacak şekilde bölünür.

16	21	11	8	12	22 – Dördüncü aşama: 16 ile 21 karşılaştırılır ve 16 küçük olduğu için yer değiştirme olmaz. 8 ile 12 karşılaştırılır ve 8 küçük olduğu için yer değiştirme olmaz.

16,21		11		8,12		22 – Beşinci aşama: 16 ile 11 karşılaştırılır ve 11 küçük olduğu için en sola yer değiştirir, 16 ve 21 kendi içinde sıralı olduklarından dolayı 11’den sonra yazılırlar. 8 ile 22 karşılaştırılır ve 8 küçük olduğu için yerinde kalır, 12 ile 22 karşılaştırılır ve 12 küçük olduğu için yerinde kalır.

11,16,21	8,12,22 – Altıncı aşama: 11 ile 8 karşılaştırılır ve 8 küçük olduğu için en sola yer değiştirir. 11 ile 12 karşılaştırılır ve 11 küçük olduğu için yerinde kalır. 16 ile 12 karşılaştırılır ve 12 küçük olduğu için 11’in sağına yer değiştirir. 16 ile 22 karşılaştırılır ve 16 küçük olduğu için yerinde kalır. 21 ile 22 karşılaştırılır ve 21 küçük olduğu için yerinde kalır. Son kalan rakam da en sağ tarafta yerinde kalır.

8,11,12,16,21,22 – Sıralama sona erer.


Big-O Gösterimi: O(nLogn)
