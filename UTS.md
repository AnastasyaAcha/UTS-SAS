Anastasya Rahma Juniarti / 1202190058 / IT0201
### Ujian Tengah Semester Sistem Administrasi Server 
#### Tutorial Install Windows Server 2022 Pada Virtual Box
## Instalasi Windows Server 2020
- Download Windows Server pada link ini [Windows Server 2022](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022)
  ```bash
  Download Windows Server. Pilih Download iso
  ```
  <img src="Pict-UTS-SAS/1.png">

  Isi data diri
  ```bash
  Isi data diri lalu continue
  ```
  <img src="Pict-UTS-SAS/2.png">

  Pilih bahasa yang akan digunakan
  ```bash
  Pilih bahasa lalu klik download
  ```
  <img src="Pict-UTS-SAS/3.png">

  ```bash
  Pilih save file. File akan terdownload
  ```
  <img src="Pict-UTS-SAS/4.png">

  ```bash
  Klik New
  ```
  <img src="Pict-UTS-SAS/50.png">

  ```bash
  Beri nama pada mesin vm
  ```
  <img src="Pict-UTS-SAS/6.png">

  ```bash
  Tentukan ukuran memory (RAM)
  ```
  <img src="Pict-UTS-SAS/7.png">

  ```bash
  Buat virtual harddisk
  ```
  <img src="Pict-UTS-SAS/8.png">

  ```bash
  Pilih VDI
  ```
  <img src="Pict-UTS-SAS/9.png">

  ```bash
  Pilih Dinamically Allocated
  ```
  <img src="Pict-UTS-SAS/10.png">

  ```bash
  Tentukan Ukuran memory harddisk
  ```
  <img src="Pict-UTS-SAS/11.png">

  ```bash
  Pilih "Windows Server 2022" lalu tekan start
  ```
  <img src="Pict-UTS-SAS/12.png">

  ```bash
  Pilih disk untuk menginstall sistem operasi. Jika tidak ada, pilih dari file
  ```
  <img src="Pict-UTS-SAS/13.png">

  ```bash
  Karena masih baru, tekan "Add"
  ```
  <img src="Pict-UTS-SAS/14.png">

  ```bash
  Cari file iso yang telah terdownload. Lalu pilih
  ```
  <img src="Pict-UTS-SAS/15.png">

  ```bash
  Pilih file disk
  ```
  <img src="Pict-UTS-SAS/16.png">

  ```bash
  Klik Start
  ```
  <img src="Pict-UTS-SAS/17.png">

  ```bash
  Tunggu proses file selesai
  ```
  <img src="Pict-UTS-SAS/18.png">
  <img src="Pict-UTS-SAS/19.png">

  ```bash
  Tekan next
  ```
  <img src="Pict-UTS-SAS/20.png">

  ```bash
  Pilih Install now
  ```
  <img src="Pict-UTS-SAS/21.png">
  <img src="Pict-UTS-SAS/22.png">

  Pada opsi ini, saya memilih Datacenter Evaluation Experience (Desktop) karena fitur yang lebih lengkap dan lebih banyak
  ```bash
  Tekan next
  ```
  <img src="Pict-UTS-SAS/23.png">

  ```bash
  Centang untuk menyetujui license software lalu klik next
  ```
  <img src="Pict-UTS-SAS/24.png">

  ```bash
  Pilih custom karena sistem operasi ini baru saja diinstall
  ```
  <img src="Pict-UTS-SAS/25.png">

  ```bash
  Pilih disk space. Lalu next
  ```
  <img src="Pict-UTS-SAS/26.png">

  ```bash
  Tunggu hingga proses install selesai
  ```
  <img src="Pict-UTS-SAS/27.png">
  <img src="Pict-UTS-SAS/28.png">
  <img src="Pict-UTS-SAS/29.png">

  ```bash
  Sistem akan me-restart otomatis dalam beberapa detik
  ```
  <img src="Pict-UTS-SAS/30.png">

  ```bash
  Tunggu sistem menampilkan desktop
  ```
  <img src="Pict-UTS-SAS/31.png">
  <img src="Pict-UTS-SAS/32.png">

  ```bash
  Buat password login
  ```
  <img src="Pict-UTS-SAS/33.png">

  ```bash
  Kombinasikan password dengan uppercase, angka, dan faktor mendukung lainnya agar password lebih kuat
  ```
  <img src="Pict-UTS-SAS/34.png">

  ```bash
  Sistem menampilkan lockscreen
  ```
  <img src="Pict-UTS-SAS/35.png">

  ```bash
  Untuk mengetik password, masukkan keyboard dengan cara seperti gambar
  ```
  <img src="Pict-UTS-SAS/36.png">

  ```bash
  Ketikkan password yang telah dibuat
  ```
  <img src="Pict-UTS-SAS/37.png">
  <img src="Pict-UTS-SAS/38.png">

  ```bash
  Sistem menampilkan halaman desktop
  ```
  <img src="Pict-UTS-SAS/39.png">

  ```bash
  Sistem akan menampilkan server manager secara otomatis. Installasi selesai
  ```
  <img src="Pict-UTS-SAS/40.png">


## Instalasi Active Directory Domain Services, DNS Server, Net Framework 3.5
- Start Windows Server 2022
    ```bash
  Buka Windows PowerShell. Llau ubah nama windows agar lebih mudah menghafalkan namanya
  ```
  <img src="Pict-UTS-SAS/ad1.PNG">

  ```bash
  Restart windows server
  ```
  <img src="Pict-UTS-SAS/ad2.png">

  ```bash
  Masuk windows server, ketik server manager lalu pilih
  ```
  <img src="Pict-UTS-SAS/ad3.png">

  ```bash
  Pilih add roles and features
  ```
  <img src="Pict-UTS-SAS/ad4.png">

  ```bash
  Klik next
  ```
  <img src="Pict-UTS-SAS/ad5.png">

  ```bash
  Pilih roled-based lalu klik next
  ```
  <img src="Pict-UTS-SAS/ad6.png">

  ```bash
  Klik next
  ```
  <img src="Pict-UTS-SAS/ad7.png">

  ```bash
  Pilih Active Directory Domain Services
  ```
  <img src="Pict-UTS-SAS/ad8.png">

  ```bash
  Klik add features
  ```
  <img src="Pict-UTS-SAS/ad9.png">

  ```bash
  Pilih DNS Server
  ```
  <img src="Pict-UTS-SAS/ad10.png">

  ```bash
  Klik add features
  ```
  <img src="Pict-UTS-SAS/ad11.png">

  ```bash
  KLik next
  ```
  <img src="Pict-UTS-SAS/ad12.png">

  ```bash
  Pilih Net Framework 3.5
  ```
  <img src="Pict-UTS-SAS/ad13.png">

  ```bash
  Klik next
  ```
  <img src="Pict-UTS-SAS/ad14.png">

  ```bash
  Klik next
  ```
  <img src="Pict-UTS-SAS/ad15.png">

  ```bash
  Klik next
  ```
  <img src="Pict-UTS-SAS/ad16.png">

  ```bash
  Klik Install
  ```
  <img src="Pict-UTS-SAS/ad17.png">

  ```bash
  Tunggu proses file selesai. Lalu close
  ```
  <img src="Pict-UTS-SAS/ad18.png">
  <img src="Pict-UTS-SAS/ad19.png">
  
## Konfigurasi Promote Server to a Domain Controller
- Buka Server Manager. Pilih Promote this server to a domain controller
  ```bash
  Tekan next
  ```
  <img src="Pict-UTS-SAS/ad20.png">

  ```bash
  Pilih New forest lalu isi domain name
  ```
  <img src="Pict-UTS-SAS/ad21.png">
  
  ```bash
  Isi Password
  ```
  <img src="Pict-UTS-SAS/ad22.png">

  ```bash
  Tekan next
  ```
  <img src="Pict-UTS-SAS/ad23.png">

  ```bash
  Tekan next
  ```
  <img src="Pict-UTS-SAS/ad24.png">

  ```bash
  Tekan next
  ```
  <img src="Pict-UTS-SAS/ad25.png">

  ```bash
  Tekan next
  ```
  <img src="Pict-UTS-SAS/ad26.png">

  ```bash
  Tunggu hingga proses selesai
  ```
  <img src="Pict-UTS-SAS/ad27.png">
  
  ```bash
  Klik Install
  ```
  <img src="Pict-UTS-SAS/ad28.png">
  
  ```bash
  Tunggu hingga proses selesai
  ```
  <img src="Pict-UTS-SAS/ad29.png">

  ```bash
  Sistem akan me-restart otomatis dalam beberapa detik
  ```
  <img src="Pict-UTS-SAS/ad30.png">

  ```bash
  Tunggu sistem menampilkan lockscreen
  ```
  <img src="Pict-UTS-SAS/ad31.png">
  
  ```bash
  Input keyboard lewat virtual box
  ```
  <img src="Pict-UTS-SAS/ad32.png">

  ```bash
  Ketikkan password. Pada step ini, nama Windows server sudah terganti
  ```
  <img src="Pict-UTS-SAS/ad33.png">

  ```bash
  Buka Network setting
  ```
  <img src="Pict-UTS-SAS/ad34.png">

  ```bash
  Pilih Change Adaptor Setting
  ```
  <img src="Pict-UTS-SAS/ad35.png">

  ```bash
  Pilih ethernet
  ```
  <img src="Pict-UTS-SAS/ad36.png">

  ```bash
  Pilih properties
  ```
  <img src="Pict-UTS-SAS/ad37.png">
  
   ```bash
  Pilih IPv4
  ```
  <img src="Pict-UTS-SAS/ad38.png">

  ```bash
  Isi Kolom DNS dengan IP
  ```
  <img src="Pict-UTS-SAS/ad39.png">

  ```bash
  Sistem akan menampilkan yang awalnya "Network 2" menjadi "sas.local". Maka konfigurasi telah berhasil
  ```
  <img src="Pict-UTS-SAS/ad40.png">


Demikian Laporan ini untuk memenuhi syarat penilaian UTS System Adminstrasi Server

  
  
  
  
  
  
  
