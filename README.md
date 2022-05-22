# Machine Learning Californian Housing Price

## Business Problem
---
Seiring berjalannya waktu, penduduk di Dunia terus mengalami peningkatan yang mengakibatkan banyaknya individu ataupun keluarga yang membutuhkan tempat tinggal / rumah untuk tempat bernaung yang sesuai dengan tingkat kemampuan seseorang tersebut dalam membeli rumah.
Yang mana hal ini menjadi tantangan untuk pihak __Penyedia Rumah__ untuk mengetahui rumah seperti apa yang akan dibangun di suatu lokasi dengan memperhitungkan tingkat `pendapatan penduduk`, lokasi `latitude` dan `longitude`, tingkat kepadatan `populasi`, maupun `jumlah kamar` yang dibutuhkan oleh keluarga dengan `jumlah keluarga yang ada (household)`.

## Goals
---
Dataset yang digunakan adalah Californian House Price yang dimana pada Project kali ini membuat machine learning untuk memprediksi harga rumah, yang dimana pada hasil akhir akan menampilkan model terbaik untuk memprediksi harga rumah yang akan dibangun ataupun yang sudah ada agar sesuai untuk divisi marketing pasarkan dan diharapkan dapat meningkatkan pemasaran dengan harga dan unit rumah yang tepat.

## Machine Learning
---
Pada proses pembuatan machine learning sebelumnya perlu dilakukan dulu `data cleaning`, `feature selection` dan `feature engineering`.
Pada Machine Learning yang dibuat ini menggunakan Regresi / Regression yang dimana pada hasil akhirnya akan menghasilkan prediksi harga yang akan ditampilkan dengan berbagai features akan akan di input oleh user.
Lalu pada proses pembuatan machine learning kali ini menggunakan metode **Pipeline**.


## Penggunaan Model
---
Untuk Model yang digunakan terdapat 5 model yaitu:

- Support Vector Regression (SVR)
- K-Nearest Neighbors (KNN)
- Decision Tree (DTree)
- Random Forest (RF)
- XGBoost (XGB)

Dari ke 5 model tersebut nantinya model base terbaik akan dilakukan Tuning sehingga akan menghasilkan nilai yang lebih baik dalam memprediksi hasil yang diinginkan.


## Conclusion dan Recommendation
---
Setelah model terbaik di Tuning maka akan terlihat perbedaannya, lalu setelah itu dilakukan pengecekan Error untuk melihat kapan model dapat dipercaya dan kapan model tidak dapat dipercaya, setelah itu dapat di lakukan:
- Conclusion, yang mana menarik kesimpulan dari Machine Learning yang telah dibuat
- Recommendation, yang mana memberi rekomendasi berdasarkan dari Conclusion yang ada, tujuannya agar dapat meningkatkan Prediksi Machine Learning yang telah dibuat agar lebih tepat dengan Error yang sedikit.


## Save and Load Model
---
Model terbaik yang sudah dibuat di Save menggunakan Pickle agar dapat digunakan user nantinya