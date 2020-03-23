| **Project Name** : IDProo Automation Test |
| --- |
| **Test Description** : Proses testing pengelolaan daftar jabatan sementara yang diberikan kepada _user_, dapat mengubah, menghapus data jabatan sementara. |


| **Test Details** | **Test Details** |
| --- | --- |
| **Test Case ID** : test 14 | **Test Priority(Low/Medium/High)** : Medium |
| **Test Case Name** : Manage Temporary Positions List Test | **Test Designed and Executed By** : Rafi |
| **Module Name** : User Story Id.14 | **Test Designed and Executed Date** : 23 Februari 2020 |


| No | Action | URL | Test Data | Screenshot | Expected Output | Actual Output | Browser | Test Result | Test Comment |   
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Klik ikon IDProo ![logo_idproo](_static/logo_idproo.jpg/?sanitize=true) | (https://idproo.id) |   | ![ss 01](_static/ss_01.png/?sanitize=true) | Web akan membuka tab baru dengan url (https://idproo.id/Identity) | Web akan membuka tab baru dengan url (https://idproo.id/Identity) | Chrome ver. 80.0.3987.106 | Pass | Rafi [03/03/2020] |
| 2  | Klik pada Submenu Temporary pada Menu Positions  | [https://idproo.id/Identity](https://idproo.id/Identity) |   | ![ss 02](_static/ss_02.png/?sanitize=true) | Sistem diharapkan dapat menampilkan daftar posisi/jabatan sementara yang ada pada user | Sistem dapat menampilkan daftar daftar posisi/jabatan sementara yang ada pada user | Chrome ver. 80.0.3987.106 | Pass | Rafi [03/03/2020 |
| 3 | Tambah Posisi/Jabatan Sementara   |   | Application : Is Owner : Checked  | ![ss 03](_static/ss_03.png/?sanitize=true) | System diharapkan mampu menerima dan menyimpan penambahan posisi/jabatan sementara | System mampu menerima dan menyimpan penambahan posisi/jabatan sementara # Sebaiknya muncul notifikasi pada saat berhasil atau gagal menambahkan posisi/jabatan sementara baru dan melakukan refresh secara otomatis  | Chrome ver. 80.0.3987.106 | Pass (With A Note) | Rafi [03/03/2020 |   |
| 4 | Edit Posisi/Jabatan Sementara |   |   | ![ss 04](_static/ss_04.png/?sanitize=true) | System diharapkan mampu menerima dan menyimpan perubahan data pada posisi / jabatan sementara | System diharapkan mampu menerima dan menyimpan perubahan data pada posisi / jabatan sementara # masih terdapat miss  pada ikon mouse dan tanda disable pada menu update dan delete  # sebaiknya system dapat memberikan notifikasi apabila user berhasil atau gagal melakukan update data posisi/jabatan. | Chrome ver. 80.0.3987.106 | Pass (With Some Notes) | Rafi [03/03/2020] |
| 5 | Cari Posisi/Jabatan |   | Searh Keyword :apalah | ![ss 05](_static/ss_05.png/?sanitize=true) | System diharapkan mampu melakukan proses pencarian data berdasarkan keyword yang diinputkan | System mampu melakukan proses pencarian data berdasarkan keyword yang diinputkan dan menampilkannya # ikon sort masih butuh 2x klik sebelum berfungsi normal | Chrome ver. 80.0.3987.106 | Pass (With a Note) | Rafi [03/03/2020] |
| 6 | Hapus Posisi/Jabatan |   | Delete : jabatan tester apalah | ![ss 06](_static/ss_06.png/?sanitize=true) ![ss 07](_static/ss_07.png/?sanitize=true) | System diharapkan mampu melakukan proses penghapusan data | System mampu melakukan proses penghapusan data # masih terdapat miss  pada ikon mouse dan tanda disable pada menu update dan delete   | Chrome ver. 80.0.3987.106 | Pass (With A Note) | Rafi [03/03/2020] |   |