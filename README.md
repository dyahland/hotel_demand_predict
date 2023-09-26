# hotel_demand_predict
The dataset contains data from two different hotels. One Resort hotel and one City hotel. The data contains "bookings due to arrive between the 1st of July of 2015 and the 31st of August 2017".

# BUSINESS PROBLEM UNDERSTANDING

### **CONTEXT**

- Perusahaan perhotelan kelas menengah, Hotel Portugal, di Portugal yang memiliki dua unit hotel di pusat kota dan di tepi pantai mencatatkan banyak sekali reservasi dari para calon penyewa hotel dari tahun 2015-2017. Namun di antara reservasi tersebut banyak yang berakhir batal. Hal ini mengisyaratkan perlunya dilakukan perbaikan sistem reservasi sehingga hotel mengetahui calon penyewa hotel mana yang benar-benar akan menginap dan mana yang membatalkannya, dilakukan untuk memaksimalkan pemesanan kamar demi mengantisipasi potensi hilangnya pendapatan pada saat musim ramai. Informasi-informasi terkait data diri dan detail pemesanan ada di tangan calon penyewa.

**STAKEHOLDER**

- Manajemen Operasional Hotel

**PROBLEM STATEMENT**

- Pada musim ramai seperti saat liburan musim panas, banyak sekali pengunjung yang akan pergi berlibur dan membutuhkan hotel untuk menginap. Hal ini membuat permintaan reservasi penuh pada saat-saat tertentu. Namun ada beberapa penyewa yang membatalkan reservasinya karena alasan-alasan tertentu. Hal ini akan berdampak pada pengurangan pendapatan pada hotel karena konsumen potensial (yang mungkin tidak batal) tak dapat membuat reservasi di tanggal yang diinginkan karena sistem menunjukkan bahwa kamar hotel telah penuh. Padahal bisa jadi pada akhirnya kamar tersebut bisa disewakan pemesan sebelumnya membatalkan reservasinya. Maka dari itu perusahaan meminta kelompok, sebagai data scientist, untuk mengelola model yang akan memprediksi batal/tidaknya sebuah reservasi yang kemudian dijadikan referensi pembatalan otomatis oleh sistem.

**GOALS**
- Dari permasalahan yang telah diuraikan diatas maka hotel berupaya untuk mengetahui calon pemesan mana yang akan berakhir check-in atau membatalkan reservasi sehingga dapat mengurangi jumlah pembatalan dan meningkatkan jumlah pengunjung yang benar-benar check-in. Setelah mengetahui calon penyewa mana saja yang akan membatalkan pemesanannya, pihak hotel dapat mengembangkan sistem pemberitahuan otomatis kepada pelanggan yang memiliki kecenderungan untuk membatalkan pemesanan. Memberi mereka opsi untuk melakukan DP atau mendapatkan penawaran khusus.  Hal ini bertujuan agar hotel dapat mengurangi risiko kerugian jika pemesanan tersebut akhirnya dibatalkan, dan pada saat yang sama, memberikan calon penyewa kesempatan untuk mempertimbangkan kembali keputusan mereka sebelum pembatalan. Dengan demikian, hotel dapat meningkatkan efisiensi dalam manajemen reservasi dan potensial meningkatkan pendapatan mereka.
- Selain itu pihak hotel juga ingin mengetahui karakteristik dari calon penyewa yang memiliki peluang besar untuk tidak membatalkan pemesanannya, sehingga hotel akan memaksimalkan operasional hotel mereka pada sektor tersebut.
