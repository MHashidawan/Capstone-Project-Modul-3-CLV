# Capstone-Project-Modul-3-CLV
 Machine Learning Analisyst on Customer Lifetime Value

# Background
_Customer Lifetime Value_ atau CLV adalah suatu ukuran terkait berpengaruhnya suatu customer terhadap perusahaan. Dari nilai tersebut, perusahaan dapat menentukan jumlah keuntungan yang akan didapatkan dari satu pelanggan dan biaya yang akan dikeluarkan untuk memperoleh pelanggan baru atau mempertahankan pelanggan lama. Hal ini berguna agar perusahaan dapat secara efektif menargetkan pemasaran kepada pelanggan yang tepat dan bagaimana mengoptimalkan pelanggan perusahaan dalam jangka waktu panjang.

# Problem Statement
_Customer Lifetime Value_ dapat dihitung melalui analisis data historis interaksi pelanggan dengan perusahaan. Dalam konteks perusahaan asuransi, perhitungan ini melibatkan pengurangan total premi yang dibayarkan dari klaim dan biaya operasional yang dikeluarkan oleh perusahaan untuk pelanggan tersebut. Meskipun demikian, jika hanya mengandalkan data historis untuk menghitung CLV dapat memakan waktu yang cukup lama disebabkan durasi yang komprehensif dari hubungan pelanggan dengan perusahaan. Jika hal ini terjadi akan menyebabkan keterlambatan untuk menerapkan keputusan bisnis strategis, seperti penawaran perpanjangan asuransi. Oleh karena itu, diperlukan metode prediktif untuk memperkirakan CLV dengan lebih efisien.

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


