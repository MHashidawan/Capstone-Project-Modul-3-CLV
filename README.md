# Capstone-Project-Modul-3-CLV
 Machine Learning Analisyst on Customer Lifetime Value

# Background
Customer lifetime value atau CLV adalah suatu ukuran seberapa berharga suatu customer terhadap perusahaan. Dari nilai tersebut, perusahhan dapat menentukan berapa keuntungan yang dipatkan dari satu penumpang dan biaya yang dikeluarkan untuk memperoleh customer baru atau mempertahankan customer lama. Angka ini cukup penting diketahui oleh suatu perusahaan jika perusahaan ingin secara efektif menargetkan pemasaran kepada pelanggan yang berharga dan bagaimana pelanggan perusahaan tersebut berubah kedepannya.

# Problem Statement
Lifetime value bisa  dihitung berdasarkan data dari sejarah customer bersama perusahaan, dalam konteks perusahaan asuransi bisa dihitung berdasarkan total premi yang dibayarkan dikurang klaim dan biaya oprasional yang dikelurakan oleh perusahaan pada customer tersebut. Menghitung customer lifetime value berdasarkan sejarahnya membutuhkan cukup banyak waktu (menghitung keseluruhan waktu customer bersama perusahaan). Saat perhitungan sudah selesai, strategi bisnis mungkin sudah terlambat diberlakukan. Contohnya pada penawaran perpanjangan asuransi. Diperlukan metode yang dapat memprediksi customer lifetime value.

# Analytic Approach

1. Melakukan Explantory Data Analysis (EDA) pada dataset. 
2. Melakukan Feature Engineering pada feature jika dibutuhkan.
3. Melakukan Preprocessing pada dataset.
4. Melakukan Benchmarking pada beberapa model regressi untuk memilih model yang paling tepat untuk dataset.
5. Melakukan Hyperparameter Tuning pada model terpilih untuk mendapatkan hasil error yang lebih rendah.



# Data Understanding
 **Attributes Information**

|Features|Deskripsi|
|-----|-----|
|Vehicle Class|Tipe kendaraan customer|
|Coverage|Tipe proteksi yang diberikan pada kendaraan|
|Renew Offer type|Tipe penawaran pembaharuan asuransi|
|Employment Status|Status pekerjaan customer|
|Marital Status|Status Pernikahan customer|
|Education|Tingkat pendidikan customer
|Number of Policies|Jumlah polis|
|Monthly Premium Auto|Premi bulanan|
|Total Claim Amount|Total klaim customer|
|Income|Pemasukan customer|
|Customer Lifetime Value|Customer Lifetime value|


