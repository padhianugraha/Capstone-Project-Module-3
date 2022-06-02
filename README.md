# California Housing Price

## **Contents**

1. Business Problem Understanding
2. Data Understanding
3. Data Preprocessing
4. Modeling
5. Conclusion
6. Recommendation

### **Business Problem Understanding**

**Context**

California adalah negara bagian yang paling banyak penduduknya dan ketiga terluas wilayahnya di Amerika Serikat. Banyaknya penduduk California disebabkan California merupakan salah satu wilayah perputaran perekonomian terbesar dari segi pertanian, entertainment dan wisata. Pada dataset ini membahas tentang harga rumah-rumah yang berada di distrik California.

**Problem Statement**

Permasalahan pada harga sensus California, **Nilai median rumah untuk rumah tangga di California**

**3. Goals**

Untuk memprediksi nilai median rumah (median house value) di California

**4. Analytics Approach**

Menentukan nilai median rumah dengan pengaruh fitur-fitur ada, melakukan analisis data untuk mengetahui informasi dari data yang ada. Selanjutnya, membangun algoritma untuk menemukan model regresi. Menemukan fitur yang berpengaruh besar terhadap target median model value.

**5. Metric Evaluation**

Evaluasi Metrik yang akan digunakan untuk model regresi yang dibangun adalah RMSE, MAE, dan MAPE, di mana RMSE adalah nilai rataan akar kuadrat dari error, MAE adalah rataan nilai absolut dari error, sedangkan MAPE adalah rataan persentase error yang dihasilkan oleh model regresi. Semakin kecil nilai RMSE, MAE, dan MAPE yang dihasilkan, berarti model semakin akurat dalam memprediksi harga sewa sesuai dengan limitasi fitur yang digunakan.

### **Data Understanding**

- Dataset adalah hasil survey sensus perumahan di California pada tahun 1990
- Berikut feature pada dataset :
1. longitude: Ukuran seberapa jauh ke barat sebuah rumah; nilai yang lebih tinggi lebih jauh ke barat

2. latitude: Ukuran seberapa jauh ke utara sebuah rumah; nilai yang lebih tinggi lebih jauh ke utara

3. housingMedianAge: Usia rata-rata sebuah rumah dalam satu blok; angka yang lebih rendah adalah bangunan yang lebih baru

4. totalRooms: Jumlah total kamar dalam satu blok

5. totalBedrooms: Jumlah total kamar tidur dalam satu blok

6. population: Jumlah total orang yang tinggal dalam satu blok

7. households: Jumlah total rumah tangga, sekelompok orang yang tinggal dalam satu unit rumah, untuk satu blok

8. medianIncome: Pendapatan rata-rata untuk rumah tangga dalam satu blok rumah (diukur dalam puluhan ribu Dolar AS)

9. medianHouseValue: Nilai median rumah untuk rumah tangga dalam satu blok (diukur dalam Dolar AS)

10. oceanProximity: Lokasi rumah dengan laut/laut



