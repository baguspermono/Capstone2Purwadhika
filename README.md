# Capstone2Purwadhika
https://public.tableau.com/app/profile/bagus.permono/viz/Transjakarta_17507725712080/Dashboard3?publish=yes
**Latar Belakang**
Penelitian ini bertujuan untuk mendalami berbagai faktor yang dapat menyebabkan ketidakpatuhan tap out, khususnya di halte-halte dengan jumlah penumpang yang tinggi. Dengan menganalisis dan membandingkan karakteristik halte yang menunjukkan tingkat kepatuhan tap out yang berbeda-beda, penelitian ini berupaya mengidentifikasi pola, perilaku penumpang, serta kondisi operasional yang mungkin memengaruhi terjadinya ketidakpatuhan tersebut. Diharapkan, hasil penelitian ini dapat memberikan perspektif baru mengenai strategi intervensi yang dapat diterapkan oleh TransJakarta guna mencegah dan meminimalisir kasus ketidakpatuhan tap out, meningkatkan efisiensi operasional, serta memperbaiki pengalaman pengguna secara menyeluruh
**Pernyataan Masalah**
Ketidakpatuhan dalam melakukan tap out pada layanan TransJakarta tidak hanya mengakibatkan kerugian pada pendapatan operasional karena tarif perjalanan yang tidak tercatat secara akurat, tetapi juga menimbulkan ketidaknyamanan bagi penumpang akibat pemblokiran kartu. Kurangnya pemahaman yang menyeluruh mengenai faktor-faktor yang memengaruhi kepatuhan tap out menjadi hambatan dalam penerapan solusi yang efektif. Selain itu, keterbatasan data yang terintegrasi—yang meliputi aspek demografis, perilaku, dan teknis dari penumpang serta sistem tap out—membatasi kemampuan untuk merancang intervensi yang tepat dan efisien.

**Data**

Dataset dapat diakses [di sini](https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction).
* `transID`: Nomor unik untuk setiap transaksi.
* `payCardID`: Identifikasi utama dari pelanggan. Kartu yang digunakan pelanggan sebagai tiket untuk masuk dan keluar.
* `payCardBank`: Nama bank penerbit kartu pembayaran milik pelanggan.
* `payCardName`: Nama pemilik kartu sebagaimana tercantum di kartu.
* `payCardSex`: Jenis kelamin pelanggan sesuai data di kartu.
* `payCardBirthDate`: Tahun lahir pelanggan.
* `corridorID`: Nomor identitas koridor atau rute, digunakan untuk pengelompokan rute.
* `corridorName`: Nama koridor atau rute, memuat titik awal dan akhir perjalanan.
* `direction`: Menunjukkan arah rute; 0 untuk arah pergi, 1 untuk arah pulang.
* `tapInStops`: ID halte tempat pelanggan melakukan tap in.
* `tapInStopsName`: Nama halte tempat pelanggan melakukan tap in.
* `tapInStopsLat`: Koordinat lintang halte tap in..
* `tapInStopsLon`: Koordinat bujur halte tap in.
* `stopStartSeq`: Urutan halte awal pada rute saat pelanggan tap in.
* `tapInTime`: Tanggal dan waktu pelanggan melakukan tap in.
* `tapOutStops`: ID halte tempat pelanggan melakukan tap out.
* `tapOutStopsName`: Nama halte tempat pelanggan melakukan tap out.
* `tapOutStopsLat`: Koordinat lintang halte tap out.
* `tapOutStopsLon`: Koordinat bujur halte tap out.
* `stopEndSeq`: Urutan halte akhir pada rute saat pelanggan tap out.
* `tapOutTime`: Tanggal dan waktu pelanggan melakukan tap out.
* `payAmount`: Jumlah pembayaran yang dilakukan pelanggan; bisa gratis atau berbayar tergantung transaksi.
  
**Kesimpulan**


* Ketidakpatuhan tap out 3,55% berdampak pada efisiensi, pendapatan, dan kepuasan pengguna.
* Halte terpadat: BKN, Penjaringan, Senen, Monas, Kampung Rambutan. Terminal Senen mencatat ketidakpatuhan tertinggi (28,57%).
* Faktor penyebab utama:
** Pola jam & hari penggunaan
** Proporsi gender & usia
** Dominasi satu jenis kartu pembayaran
** Kurangnya edukasi & kendala teknis
* Kesimpulan Utama:
Ketidakpatuhan tap out dipengaruhi kombinasi faktor edukasi, teknis, demografis, dan pola penggunaan.
Intervensi efektif harus menyasar seluruh faktor ini: edukasi, perbaikan fasilitas, diversifikasi pembayaran, dan strategi operasional sesuai karakteristik halte untuk menjaga dan meningkatkan efisiensi, pendapatan, serta kepuasan pengguna.

[Dashboard]https://public.tableau.com/app/profile/bagus.permono/viz/Transjakarta_17507725712080/Dashboard3?publish=yes
