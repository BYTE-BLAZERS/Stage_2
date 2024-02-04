# Final-Project-Byte-Blazers - Stage 2
Final Project Kelompok 4

Stage - 2
**Summary**
1. Handling Missing Values
> - Setelah dilakukan Handling Missing Value tidak terdapat data yang hilang (missing value)

2. Handling Duplicate Values
> - Handling data duplicates bertujuan untuk mengatasi masalah ketika kita memiliki informasi yang sama atau sangat mirip dalam dataset. Ini bisa terjadi ketika kita memiliki baris yang memiliki nilai yang sama dalam beberapa kolom.
> - Dari hasil tersebut ditemukan bahwa ada data yang duplicate.

3. Handling Redundant Data
> - Data Redundant adalah suatu kondisi ketika keberadaan informasi yang berlebihan atau berulang dalam suatu dataset.
> - Penanganan data redundan penting untuk menjaga kualitas data, mengoptimalkan penggunaan sumber daya, dan mencegah kesalahan analisis yang disebabkan oleh duplikasi atau ketidaksempurnaan dalam dataset. Penanganan data redundant adalah dengan melakukan pembersihan data dan menghapus atau menggabungkan informasi yang berulang.
> - Pada dataset yang digunakan, kami tidak menemukan adanya data redundant yang perlu ditangani, Sehingga Handling Redundant Data tidak dilakukan.

4. Handling Outliers
> - Handling outliers dilakukan untuk mengatasi nilai-nilai yang sangat jauh atau tidak biasa dalam suatu dataset yang dapat mempengaruhi analisis statistik dan model prediktif, sehingga menangani mereka membantu mencegah kesalahan atau distorsi dalam interpretasi hasil analisis data.
> - setelah dilakukan proses pengecekkan outliers tidak terdapat outlier pada data.

5. Feature Encoding
> - Untuk memudahkan membangun model machine learning di tahap selanjutnya, kami akan melakukan convert ‘Yes/No’ menjadi 1/0 (binary) pada kolom GraduateOrNot, FrequentFlyer, EverTravelledAbroad dan ChronicDiseases
> - Untuk Employment Type kami akan mengubah 1/0 (binary) menjadi:
> - 1. Government Sector : 1
> - 2. Private Sector : 0

6. Feature Transformation
> - dalam membangun model Machine Learning, kami menambah feature baru berupa pengelompokan annual income untuk membantu analisis data. Pada Feature CatAnIncome terdapat 3 pengelompokan berdasarkan AnnualIncome, yaitu :
> - 1. Low (0 - 600.000)
> - 2. Mid (600.001 - 1.250.000)
> - 3. High (1.250.001 - 1.800.000)

7. Feature Engineering
> - visualisasi data dari penambahan feature engineering yang kami gunakan yaitu CatAnIncome
> - Pelanggan yang memiliki penghasilan yang tinggi cenderung akan membeli Asuransi Perjalanan

8. Normalization
> - Normalization kami lakukan untuk menjaga konsistensi skala antar fitur dalam dataset karena fitur dengan skala yang tidak seimbang dapat mempengaruhi proses Machine Learning dan analisis data.
> - Lalu kami melakukan pengecekan pada predictor variables setelah dilakukan normalisasi

9. Class Imbalanced
> - Pengecekan Class Imbalance
> - Menentukan X fitur dan y target untuk dilakukan oversampling
> - Handling imbalance data dengan resampling data
> - Pada dataset ini kami meningkatkan jumlah sampel minoritas (Government Sector) dengan menciptakan sampel sintesis menggunakan Oversampling metode SMOTE
