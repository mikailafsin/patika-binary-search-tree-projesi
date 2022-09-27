# Binary Search Tree Projesi

Merhaba, [Patika](https://www.patika.dev)'nın [Veri Yapıları Ve Algoritmalar](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar) eğitimi kapsamındaki 3. Projesini tamamladım.

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

**Dizisinin Binary-Search-Tree aşamalarını yazınız.**

***Cevap***

İkili arama ağacında ilk olarak root elemanı belirlenir. Bu root elemanı aynı zamanda ağaç yapısının ilk elemanı ve tüm diğer dizi elemanlarının da olduğu gibi node(düğüm) terimine karşılık gelir.

İkili arama ağacı, dizi elemanlarını ağaca eklemek için root elemanını referans alarak eklemeye başlar. Eğer eklenecek eleman, o an karşılaştırılması yapılan düğüm elemanından küçük ise düğümün soluna, büyük ise düğümün sağına eklenerek ağaç oluşturulur.

Ağacı oluşturmaya root elemanını yani dizinin ilk elemanı olan 7'yi seçerek başlıyoruz. Ardından dizinin bir sonraki elemanı için yukarıda anlatılmış olan aşamaları uyguluyoruz. Sonuç olarak alttaki tabloda görünen ağacı elde etmiş oluyoruz.

|   |    |    | 7  |    |    |
| - | -- | -- | -- | -- | -- |
|   |    | /  |    | \\ |    |
|   |    | 5  |    | 8  |    |
|   | /  |    | \\ |    | \\ |
|   | 1  |    | 6  |    | 9  |
| / |    | \\ |    |    |    |
| 0 |    | 3  |    |    |    |
|   | \\ |    |    |    |    |
|   | 2  |    |    |    |    |
