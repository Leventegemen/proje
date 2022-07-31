# Insertion-Sort
Sıralama algoritmasıdır. Küçükten büyüğe sıralar. 
## Verilen Diziyi Insertion Sort algoritmasına göre sıralayınız.
[22,27,16,2,18,6]
- "-- sayı --" aradığımız küçük sayıyı ifade ediyor.
- "- sayı -" hangi sayı küçük sayı ile yer değiştirecek onu ifade ediyor.
- 
- [-22-,27,16,--2--,18,6] // Dizinin içindeki en küçük elemanı buldum ve ilk elemanla yer değiştirdim.
- [2,27,16,22,18,6]       // 1. adımdan sonra elde ettiğim dizinin son hali.
- [2,-27-,16,22,18,--6--] // Artık dizinin içinden en küçük ikinci elemanı bulup ikinci elemanla yer değiştirmem gerek.
- [2,6,16,22,18,27] // 2. adımdan sonra elde ettiğim dizinin son hali.
- [2,6,- --16-- -,22,18,27] // Dizinin üçüncü elemanı ile üçüncü en küçük elemanı bulup yer değiştirmem gerek.
- [2,6,16,22,18,27] // 3. adımda zaten 16 olması gereken yerde olduğu için aynı yerde kaldı.
- [2,6,16,-22-,--18--,27] // Dizinin dördüncü elemanı ile dördüncü en küçük elemanı yer değiştirecek.
- [2,6,16,18,22,27] // Gördüğünüz gibi dizi küçükten büyüğe sıralandı. 
- İşlemlerimiz bitti.
### Time Complexity
- Average case: Aradığımız sayının ortada olması. O(n²)
- Worst case: Aradığımız sayının sonda olması. O(n²)
- Best case: Aradığımız sayının dizinin en başında olması. O(n)
- Yukarıda verilen diziyi sıraladık. ==> [2,6,16,18,22,27] 
- Yukarıda verilen tanımlara da bakarak 18 sayısı hangi case kapsamına girer sorusunun cevabı AVARAGE case olur
## Insertion Sort Big-O Gösterimi
- Big-O Gösterimi : O(n²)
