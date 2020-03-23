Pengujian sistem adalah pengujian program perangkat lunak yang lengkap dan terintegrasi. Perangkat lunak atau yang sering dikenal dengan sebutan _software_ hanyalah satuan elemen dari sistem berbasis komputer yang lebih besar. Biasanya, perangkat lunak dihubungkan dengan perangkat lunak dan perangkat keras lainnya.

Pengujian perangkat lunak dapat dibedakan menjadi dua yaitu _Black Box Testing_ dan _White Box Testing_.

- **Black Box Testing**

 ![sample_01](_static/sample_01.png/?sanitize=true)

_Black Box Testing_ atau yang sering dikenal dengan sebutan pengujian fungsional merupakan metode pengujian Perangkat Lunak yang digunakan untuk menguji perangkat lunak tanpa mengetahui struktur internal kode atau Program. Dalam pengujian ini, _tester_ menyadari apa yang harus dilakukan oleh program tetapi tidak memiliki pengetahuan tentang bagaimana melakukannya.

Kelebihan _Black Box Testing_ yaitu:

1. Efisien untuk segmen kode besar
2. Akses kode tidak diperlukan
3. Pemisahan antara perspektif pengguna dan pengembang

Kelemahan _Black Box Testing_ yaitu:

1. Cakupan terbatas karena hanya sebagian kecil dari skenario pengujian yang dilakukan
2. Pengujian tidak efisien karena keberuntungan _tester_ dari pengetahuan tentang perangkat lunak internal

- **White Box Testing**

 ![sample_02](_static/sample_02.png/?sanitize=true)

_White Box Testing_ merupakan metode pengujian perangkat lunak di mana struktur internal diketahui untuk menguji siapa yang akan menguji perangkat lunak. Pengujian ini membutuhkan pengetahuan internal tentang kemampuan sistem dan pemrograman.

Kelebihan _White Box Testing_ yaitu:

1. Efisien dalam menemukan kesalahan dan masalah
2. Diperlukan pengetahuan tentang internal perangkat lunak yang sedang diuji bermanfaat untuk pengujian menyeluruh
3. Memungkinkan menemukan kesalahan tersembunyi
4. Membantu mengoptimalkan kode

Kelemahan _White Box Testing_ yaitu:

1. Membutuhkan pengetahuan tingkat tinggi dari perangkat lunak internal yang sedang diuji
2. Membutuhkan akses kode

**Hirarki Pengujian Perangkat Lunak**

 ![sample_03](_static/sample_03.png/?sanitize=true)

Pengujian perangkat lunak memiliki urutan-urutan mengenai beberapa hal yang perlu dilakukan. Berikut adalah kategori pengujian perangkat lunak yang disusun secara kronologis:

_Unit Testing_: Pengujian dilakukan pada setiap modul atau blok kode selama pengembangan. Pengujian ini biasanya dilakukan oleh _developer_ yang menulis kode.

_Integration Testing_: Pengujian yang dilakukan Sebelum, selama, dan setelah integrasi modul baru ke dalam paket perangkat lunak utama. Pengujian ini melibatkan pengujian setiap modul kode dari masing-masing individu. Satu perangkat lunak dapat berisi beberapa modul yang sering dibuat oleh beberapa _developer_ yang berbeda.

_System Testing_: Pengujian yang dilakukan oleh agen pengujian profesional pada produk perangkat lunak yang telah selesai sebelum perangkat lunak tersebut diperkenalkan secara umum.

_Acceptance Testing_: Pengujian beta dari produk yang dilakukan oleh pengguna akhir yang sebenarnya.

**Jenis Pengujian Sistem**

 ![sample_04](_static/sample_04.png/?sanitize=true)

Terdapat sekitar 50 jenis pengujian sistem. Dari 50 jenis tersebut, terdapat beberapa pengujian sistem yang biasanya digunakan oleh perusahaan pengembang _software_ atau perangkat lunak besar. Beberapa jenis tersebut diantaranya yaitu:

_Usability Testing_: Pengujian ini berfokus pada kemudahan pengguna dalam menggunakan aplikasi, fleksibilitas dalam menangani kontrol dan kemampuan sistem untuk memenuhi tujuannya.

_Load Testing_: Pengujian ini diperlukan untuk mengetahui bahwa solusi perangkat lunak akan bekerja di bawah beban nyata.

_Regression Testing_: Pengujian ini melibatkan pengujian yang dilakukan untuk memastikan bahwa tidak ada perubahan yang dibuat selama proses pengembangan telah menyebabkan _bug_ baru. Hal ini juga digunakan untuk memastikan tidak ada _bug_ lama yang muncul dari penambahan modul perangkat lunak baru dari waktu ke waktu.

_Recovery Testing_: Pengujian ini dilakukan untuk menunjukkan solusi perangkat lunak dapat diandalkan, dapat dipercaya, dan dapat berhasil menutup kemungkinan terjadinya _crash_.

_Migration Testing_: Pengujian ini dilakukan untuk memastikan bahwa perangkat lunak sistem dapat dipindahkan dari infrastruktur sistem lama ke infrastruktur infrastruktur sistem saat ini tanpa terjadi masalah.

_Functional Testing_ atau _Completeness Testing_: Pengujian ini memerlukan pemikiran mengenai kemungkinan terjadinya fungsi yang hilang. Penguji membuat daftar fungsional tambahan yang bisa dikembangkan oleh suatu produk selama proses pengujian fungsional.

_Hardware/ Software Testing_: Pengujian ini terjadi ketika penguji fokus pada interaksi antara perangkat keras dan perangkat lunak sistem selama proses pengujian sistem.