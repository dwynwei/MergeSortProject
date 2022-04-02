# MergeSortProject

                                [22,27,16,2,18,6] -> Merge Sort
                                
1.	[22,27] – [16] -------- [2,18]  -- [6]   Dizi sayısına göre sayılar 2 li ayrılabiliryorsa ayrılır.
2.	Ilk 2’li ayırmada 22 ve 16 karşılaştırılıp küçük olan sayı başta olacak şekilde 3 elemanlı dizi halinde birleştirilir.   [16,22,27]
3.	Aynı durum ayrılan sağ taraftaki 2 dizi içinde yapılır  [2,6,18]
4.	[16,22,27] ile [2,6,18] kendi aralarında eleman sıralarına göre kıyaslanır
5.	[2,6,18,16,22,27] şeklinde sıralaması gerçekleşir.
6.	Time Compexity’si n eleman üzerinde dolaşarak ve dizileri bölerek gittiğimiz için exponential bir çizgi izlememizden kaynaklı 1 e kadar iner. logn time complexity ile gösterilir. Tüm durum için ise
Time Complexity O(nlogn) olur
