<div align="center">

## LAPORAN PRAKTIKUM SISTEM OPERASI

## INTSALLASI SISTEM OPERASI LINUX-UBUNTU

Dosen Pengampu:\
Ahmad Heryanto, M. T.\
Adi Hermansyah, M. T.\
Sutarno, M.T.\
Iman Saladin B. Azhar, S. Kom., M. M.SI.\
Dr. Ahmad Zarkarsi, M. T.

![Logo Universitas Sriwijaya](https://github.com/SyaifulKaromah/foto-repo/blob/afa46f9c1746a24004c7106948d9a7adcf28a5be/1639367926_61ac53fbb7fda3f5b72f.png)

Disusun Oleh:\
Nama: Yesi Paramita\
NIM: 09011182328116\
Hari/Tanggal: Kamis, 29 Agustus 2024

JURUSAN SISTEM KOMPUTER  
FAKULTAS ILMU KOMPUTER  
UNIVERSITAS SRIWIJAYA  
2024
<br>
<br>

## Daftar Isi

</div>

>
[Pendahuluan](#pendahuluan)
  > [Latar Belakang](#latar-belakang)\
  > [Tujuan](#tujuan)\
  > [Landasan Teori](#landasan-teori)

>
[Alat dan Bahan](#alat-dan-bahan)
  
>
[Prosedur](#prosedur)

>
[Hasil dan Pembahasan](#hasil-dan-pembahasan)
  > [Hasil](#hasil)\
  > [Pembahasan](#pembahasan)

>
[Kesimpulan](#kesimpulan)

>
[Daftar Pustaka](#daftar-pustaka)

<div align="center">
<br>
<br>

## Pendahuluan

</div>

### Latar Belakang

<div align="justify">

Ubuntu adalah distribusi Linux yang dikembangkan oleh Canonical Ltd. dan pertama kali dirilis pada 20 Oktober 2004. Berbasis Debian, Ubuntu dirancang untuk kemudahan penggunaan, kestabilan, dan aksesibilitas, menjadikannya pilihan populer bagi pengguna baru maupun berpengalaman. 
Ubuntu menawarkan antarmuka pengguna yang ramah, keamanan tinggi, dan akses ke ribuan aplikasi melalui Ubuntu Software Center. Dukungan jangka panjang (LTS) dan komunitas yang aktif juga merupakan keunggulan utama Ubuntu. Selain untuk desktop, Ubuntu juga tersedia dalam versi server dan varian lain yang disesuaikan untuk kebutuhan tertentu.

### Tujuan
•	Memahami langkah-langkah instalasi pada sistem operasi Linux.\
•	Mampu menganalisis proses instalasi.

### Landasan Teori
Sistem operasi adalah perangkat lunak yang berfungsi untuk mengaktifkan dan memungkinkan semua perangkat yang terpasang di komputer berkomunikasi satu sama lain. Pada umumnya, sistem operasi merupakan software pertama yang dimuat ke dalam memori komputer saat komputer dinyalakan. Software lain akan dijalankan setelah sistem operasi berfungsi, dan sistem operasi menyediakan layanan inti yang umum, seperti akses ke disk, manajemen memori, penjadwalan tugas, dan antarmuka pengguna. Dengan demikian, software lain tidak perlu menangani tugas-tugas ini sendiri karena sudah ditangani oleh sistem operasi. Bagian kode yang menangani tugas-tugas inti ini dikenal sebagai "kernel" dari sistem operasi.\
Oracle VM VirtualBox adalah perangkat lunak virtualisasi yang memungkinkan menjalankan sistem operasi "tambahan" di dalam sistem operasi "utama". Misalnya, jika seseorang menggunakan MS Windows sebagai sistem operasi utamanya, dia dapat menjalankan sistem operasi lain di dalam MS Windows tersebut. Fungsi ini sangat berguna untuk uji coba dan simulasi instalasi tanpa harus menggantikan sistem yang sudah ada. Aplikasi lain dengan fungsi serupa termasuk VMware dan Microsoft Virtual PC. Sistem operasi yang dapat menggunakan VirtualBox meliputi Linux, Mac OS X, Windows Vista, Windows 10, Windows 11, Solaris, dan OpenSolaris.\
Pada praktikum kali ini, kita menggunakan sistem operasi Linux, yaitu Ubuntu 22.04 LTS. Nama "Linux" diambil dari nama penciptanya, Linus Torvalds, yang memperkenalkan sistem operasi ini pada tahun 1991. Komponen sistem, alat-alat sistem, dan pustaka yang digunakan Linux sebagian besar berasal dari proyek GNU (GNU's Not UNIX), yang diumumkan oleh Richard Stallman pada tahun 1983. Karena kontribusi dari GNU ini, muncul nama alternatif GNU/Linux. Linux telah lama dikenal karena penggunaannya di server dan didukung oleh perusahaan komputer besar seperti Intel, Dell, Hewlett-Packard, IBM, Novell, Oracle Corporation, Red Hat, dan Sun Microsystems. Linux digunakan sebagai sistem operasi pada berbagai jenis perangkat keras komputer, termasuk komputer desktop, superkomputer, dan sistem tertanam seperti e-book reader, konsol permainan video seperti PlayStation 2, PlayStation 3, Xbox, serta ponsel dan router.



</div>

<div align="center">
<br>
<br>

## Alat dan Bahan

</div>

<div align="justify">

•	Modul praktikum.\
•	Seperangkat PC atau Laptop.\
•	Software Virtual box.\
•	ISO Linux (Ubuntu 24.04 LTS)


</div>

<div align="center">
<br>
<br>

## Prosedur

</div>

<div align="justify">

1.	Sambungkan personal computer pada arus listrik
2.	Hidupkan computer tunggu proses booting
3. Tekan Tombol Baru
4. Silakan buka aplikasi virtualbox, sehingga anda akan mendapati tampilannya 
seperti yang di tunjukkan pada gambar di bawah ini:


   ![Langkah 4](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step4.png)

5. Kemudian klik new untuk membuat lingkungan virtual mesin yang baru sehingga tertampil seperti pada gambar di bawah ini: Beri nama virtual mesin anda, kemudian pilih type dan versi seusuai gambar

   ![Langkah 5](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step5.png)

6. Kemudian anda akan diminta membuat alokasi memory (RAM) virtual yang akan anda gunakan nantinya, sesuaikan dengan kapastias RAM di komputer anda seperti yang ditunjukkan pada gambar di bawah: saran saya maksimal separuh dari alokasi total RAM di komputer anda

   ![Langkah 6](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step6.png)

   ![Langkah 6-2](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step6-2.png)

7. Kemudian anda akan diminta membuat virtual harddisk untuk mesin virtual anda seperti yang ditunjukkan pada gambar di bawah:

   ![Langkah 7](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step7.png)

8. Setelah selesai, anda akan melihat tampilan seperti yang ditunjukkan pada gambar di bawah, dimana anda 
telah selesai membuat seuahmeisn virtual dengan platform Ubuntu:


   ![Langkah 8](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step8.png)

9. Silakan klik Setting di sebelah tombol Add di pojok kiri atas sehingga tertampil seperti pada gambar di bawah, untuk melakukan setting Display,untuk mengsetting memory dan minitor count,seperti gambar di bawah

    ![Langkah 9](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step9.png)

10. Setelah itu kita klik star dan tampilannya akan seperti ini:

    ![Langkah 10](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step10.png)

11. Kemudian kita nextkan terus sampai terdapat kata instal seperti gambar berikut:

![Langkah 11](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step11.png)

Setelah kita lakukan instal tampilanya akan seperti ini:

![Langkah 12](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step12.png)

12. Setelah itu kita tunggu proses instalasinya sampai selesai dan ubuntu sudah siap, bisa kita jalankan.Tampilannya akan seperti ini

![Langkah 13](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step13.png)

13.	Selanjutnya klik start disebelah discard untuk membuka atau menjalakan ubuntu di virtualbox. Tampilan setelah kita klik start tadi akan seperti ini,jika sudah seperti ini ubuntu sudah siap digunakan.

![Langkah 14](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/loading.png)

15. Kemudian, "Restart now"

![Langkah 15](https://github.com/SyaifulKaromah/foto-repo/blob/c9f20bf27a7fc03518c6200053bb3de74a7459e6/restartnow.png)

![Langkah 15-2](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/booting.png)

16. Ubuntu telah selesai di install

</div>

   ![Langkah 16](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/selesai.png)


<div align="center">
<br>
<br>

## Hasil dan Pembahasan

</div>

<div align="justify">

### Hasil
Hasil dari praktikum ini adalah sebagai berikut:
- [x] Berhasil menginstal dan mengatur Oracle VM VirtualBox di komputer host.
- [x] Berhasil membuat mesin virtual baru dengan spesifikasi yang tepat untuk Ubuntu:
    - Alokasi RAM: 5004 MB
    - Alokasi penyimpanan: 55 GB
    - Jumlah core prosesor: 1
- [x] Berhasil menginstal Ubuntu 24.04 LTS di mesin virtual yang telah dibuat.
- [x] Berhasil menyelesaikan konfigurasi awal Ubuntu, termasuk:
    - Pemilihan bahasa dan zona waktu
    - Pembuatan akun pengguna
    - Pengaturan koneksi jaringan
- [x] Berhasil melakukan booting ke sistem operasi Ubuntu yang baru diinstal dan memverifikasi fungsionalitas dasarnya.

### Pembahasan
Berikut adalah hasil parafrase dari teks yang diberikan:

- Persiapan dan Konfigurasi VirtualBox:\
VirtualBox digunakan untuk menginstal Ubuntu tanpa mengganggu sistem operasi host, memberikan lingkungan yang aman untuk eksperimen dan pembelajaran. Pengalokasian sumber daya seperti RAM, penyimpanan, dan core prosesor perlu diperhatikan dengan baik untuk memastikan kinerja optimal dari sistem virtual.

- Proses Instalasi Ubuntu:\
Proses instalasi Ubuntu berlangsung lancar tanpa masalah berarti. Antarmuka instalasi yang ramah pengguna mempermudah proses tersebut, bahkan untuk pemula yang baru mengenal Linux. Fitur "Try or Install Ubuntu" memungkinkan pengguna untuk mencoba sistem sebelum melakukan instalasi penuh, yang berguna untuk pengenalan awal.

- Konfigurasi Sistem:\
Konfigurasi awal Ubuntu, yang mencakup pemilihan bahasa, pengaturan zona waktu, dan pembuatan akun pengguna, berjalan dengan mulus. Hal ini menunjukkan fleksibilitas Ubuntu dalam menyesuaikan diri dengan kebutuhan pengguna dari berbagai latar belakang dan lokasi geografis.

- Performa Sistem:\
Setelah diinstal, Ubuntu berfungsi dengan baik di lingkungan virtual. Meskipun ada sedikit penurunan performa dibandingkan dengan instalasi langsung pada perangkat keras, hal ini wajar dalam konteks virtualisasi. Penggunaan VirtualBox Guest Additions dapat meningkatkan kinerja dan integrasi antara sistem host dan guest.

- Pembelajaran dan Implikasi:\
Praktikum ini memberikan wawasan penting tentang proses instalasi sistem operasi dan pengelolaan sumber daya komputer. Mahasiswa mendapatkan pemahaman langsung tentang cara menginstal dan mengonfigurasi sistem operasi, yang penting untuk pemahaman yang lebih dalam tentang operasi sistem.

- Tantangan dan Solusi:\
Beberapa tantangan yang mungkin muncul meliputi masalah kompatibilitas perangkat keras virtual dan alokasi sumber daya yang tidak memadai. Solusinya mencakup penyesuaian pengaturan VirtualBox dan pengalokasian sumber daya yang tepat.

- Penerapan Konsep Sistem Operasi:\
Praktikum ini mengilustrasikan konsep penting dalam sistem operasi seperti manajemen memori, penjadwalan prosesor, dan sistem file. Mahasiswa dapat melihat penerapan konsep-konsep ini dalam konteks nyata saat instalasi dan konfigurasi sistem.


</div>

<div align="center">
<br>
<br>

## Kesimpulan

</div>

<div align="justify">

sistem operasi adalah perangkat lunak yang memungkinkan semua perangkat yang terpasang pada komputer berfungsi dan berkomunikasi satu sama lain. Secara umum, sistem operasi adalah perangkat lunak pertama yang dimuat ke dalam memori komputer saat dinyalakan, sementara perangkat lunak lainnya dijalankan setelah sistem operasi aktif.

Berdasarkan pengertian ini, sistem operasi Linux Debian dan Ubuntu menawarkan layanan yang berbeda untuk penggunanya, sehingga masing-masing memiliki kelebihan dan kekurangan. Kedua sistem operasi ini memiliki kesamaan, seperti sifatnya yang open source, atau dengan kata lain, bebas biaya. Keduanya juga menyediakan banyak fasilitas untuk memudahkan pengguna.

Dapat disimpulkan bahwa Ubuntu adalah sistem operasi yang dikembangkan berdasarkan Debian OS. Ubuntu lebih ditujukan untuk kebutuhan bisnis, sementara Debian lebih fokus pada komunitas. Namun, preferensi tetap bergantung pada penggunanya; ada yang lebih menyukai Debian dan ada juga yang fanatik dengan Ubuntu.


</div>

<div align="center">
<br>
<br>

## Daftar Pustaka

</div>

<div align="justify">

- Praktikum 1	Sistem Operasi Linux
- Ryanal, F. (2015). Makalah.Sistem.Operasi.Linux.Debian. Retrieved from http://ryanalfians.blogspot.co.id.
- Canonical Ltd. (2024). Ubuntu Desktop for developers. https://ubuntu.com/desktop/developers
- Oracle Corporation. (2024). Oracle VM VirtualBox User Manual. https://www.virtualbox.org/manual/
- Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). Operating System Concepts (10th ed.). Wiley.
- adha, R. (2016). https://rendikadesign.blogspot.com/. Sistem Operasi.
- Ubuntu Documentation Team. (2024). Ubuntu Server Guide. https://ubuntu.com/server/docs

</div>

----
<br>
<br>

[←    BACK](#praktikum-1---sistem-operasi)
# Soal 2

## Informasi Mahasiswa
- Nama: Yesi Paramita
- NIM: 09011182328116
- Kelas: SK3B

<br>

<div asign= "justify">

## Analisislah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi mount point?

![Mount Point Selection](https://github.com/SyaifulKaromah/foto-repo/blob/e433532cee5da6d4afdc9639eebc9ae06a79300b/Mount.png)

<br>

## Jawaban

 Ada beberapa alasan mengapa saat instalasi perlu dipilih "/" pada opsi mount point:

1. Direktori Root ( / ): Tanda "/" merupakan direktori root, yang merupakan tingkat tertinggi dalam struktur sistem file.

2. Instalasi Sistem Operasi: Memilih "/" sebagai mount point berarti kita menginstal sistem operasi di direktori root.

3. Akses File dan Folder: Dengan memilih "/", kita dapat mengakses semua file dan folder di sistem. Contohnya, untuk membuka file di Desktop, jalur lengkapnya adalah "/Desktop".

4. Kemudahan Akses Jalur File: Dengan menggunakan "/" sebagai mount point, semua jalur file dapat diakses dengan mudah.

5. Standar di Linux: Hampir semua distribusi Linux menggunakan "/" sebagai direktori root.

</div>

----
<br>
<br>

[←    BACK](#praktikum-1---sistem-operasi)
# Soal 3

## Informasi Mahasiswa
- Nama: Yesi Paramita
- NIM: 09011182328116
- Kelas: SK3B

<br>

<div align="Justify">

## Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs ! 

<br>

## Jawab:

Berikut adalah penjelasan tentang Ext4, Ext3, Swap, NTFS, FAT32, dan Btrfs dalam bentuk poin:

 1. *Ext4*
   - Sistem file default di banyak distribusi Linux.
   - Mendukung file hingga 16 TiB, volume hingga 1 EiB.
   - Lebih cepat dan efisien daripada Ext3.

 2. *Ext3*
   - Pendahulu Ext4, digunakan luas di Linux sebelumnya.
   - Mendukung file hingga 2 TiB, volume hingga 32 TiB.
   - Menyediakan jurnal untuk integritas data.

 3. *Swap*
   - Memori virtual untuk Linux, bukan sistem file.
   - Digunakan ketika RAM hampir penuh.
   - Biasanya disarankan 1,5 hingga 2 kali ukuran RAM.

 4. *NTFS*
   - Sistem file default di Windows.
   - Mendukung file dan volume sangat besar (hingga 16 EiB).
   - Menyediakan enkripsi, kompresi, dan kontrol akses.

 5. *FAT32*
   - Umum digunakan pada perangkat portabel (USB, SD card).
   - Mendukung file hingga 4 GB, volume hingga 8 TiB.
   - Sederhana, dengan kompatibilitas luas.

 6. *Btrfs*
   - Sistem file modern di Linux.
   - Mendukung snapshot, kompresi, dan pemeriksaan integritas data.
   - Dirancang untuk efisiensi data skala besar.
     
</dir>
