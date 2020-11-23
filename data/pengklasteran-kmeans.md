# Proses Pengklasteran K-Means
Metode K-Means digunakan sebagai alternatif metode klaster untuk data dengan ukuran yang besar karena memiliki kecepatan yang lebih tinggi dibandingkan metode hirearki.
Mac Queen menyarankan bahwa penggunaan K-Means untuk menjelaskan algoritma dalam penentuan suatu objek ke dalam klaster tertentu berdasarkan rataan terdekat. Proses pengklasteran dengan metode K-Means adalah:

1. Mementukan besarnya **k**, yaitu banyaknya klaster.
2. Menentukan _centroid_ di tiap klaster.
3. Menghitung jarak tiap objek dengan setiap _centroid_.
4. Menghitung kembali rataan (_centeroid_) untuk klaster yang baru terbentuk.
5. Mengulangi langkah 2 sampai tidak ada lagi pemindahan objek antar klaster.