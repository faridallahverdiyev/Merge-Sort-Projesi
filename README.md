# Merge-Sort-Projesi
Verilen dizi: [16, 21, 11, 8, 12, 22]

1. **Bölme (Divide):** Dizi, ortadan ikiye bölünür.
   - Sol yarı: [16, 21, 11]
   - Sağ yarı: [8, 12, 22]

2. Sol yarının bölünmesi:
   - Sol yarının sol yarısı: [16]
   - Sol yarının sağ yarısı: [21, 11]

3. Sağ yarının bölünmesi:
   - Sağ yarının sol yarısı: [8]
   - Sağ yarının sağ yarısı: [12, 22]

4. **Birleştirme (Merge):** Bölünmüş parçalar sıralı olarak birleştirilir.
   - Sol yarının sağ yarısı sıralanır: [11, 21]
   - Sağ yarının sağ yarısı sıralanır: [8, 12, 22]

5. Sol yarının iki parçası birleştirilir: [16] ve [11, 21] -> [11, 16, 21]
6. Sağ yarının iki parçası birleştirilir: [8] ve [12, 22] -> [8, 12, 22]

7. Son olarak, sol ve sağ yarının birleştirilmiş halleri birleştirilir: [11, 16, 21] ve [8, 12, 22] -> [8, 11, 12, 16, 21, 22]

Big-O gösterimi: Merge Sort'un en iyi, ortalama ve en kötü durumlardaki zaman karmaşıklığı O(n log n)'dir.
