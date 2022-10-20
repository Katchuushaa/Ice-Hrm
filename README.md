IceHrm
==========
**IceHrm** merupakan sebuah aplikasi web "Human Resources Management" atau manajemen sumberdaya manusia yang memungkinkan perusahaan untuk mengelola aktivitas SDM dengan benar dan lengkap.
Fungsi utama dari aplikasi IceHrm ini adalah menjadi sebuah sistem manajemen karyawan memungkinkan perusahaan untuk memusatkan informasi rahasia karyawan.

# Instalasi


#### Kebutuhan Sistem :
- Unix, Linux atau Windows.
- Docker

#### Proses Instalasi :
1. Install [Docker](https://docs.docker.com/get-docker/) terlebih dahulu sebelum melakukan instalasi IceHrm.
2. Jika proses instalasi Docker sudah selesai, lakukan proses git clone untuk mendownload file [IceHrm](https://github.com/gamonoid/icehrm.git) pada terminal.
    ```
    $ git clone https://github.com/gamonoid/icehrm.git
    ```
3. Pindahkan directory untuk mengakses file **IceHrm** yang sudah didownload.
    ```
    $ cd icehrm
    ```
4. Buat file dengan nama **icehrm.log** pada app/data.
    ```
    $ touch app/data/icehrm.log
    *jika tidak bisa maka buat secara manual seperti pada video
    ```
5. Lakukan **compose-files** untuk dapat menjalankan container dari **IceHrm**.
    ```
    $ docker-compose -f docker-compose-prod.yaml up -d
    ```
6. Jika proses **docker-compose** sudah selesai, kita dapat mengakses **IceHrm** dengan mengunjungi pada [localhost](http://localhost:8070/).

7. Untuk mengakses **IceHrm** lebih lanjut dapat melakukan login dengan username = admin dan password = admin.

# Docker
Fungsi dari **Docker** adalah untuk menyatukan beberapa file dalam sebuah program software. Nah, file-file pendukung yang ada disebut juga image dan dikumpulkan menjadi satu dalam sebuah wadah yang dinamakan container. Container ini menjadi sebuah alat untuk penyimpanan file dan docker merupakan platform yang dibangun dengan teknologi container sebagai dasarnya.

# Kelebihan
- Salah satu sistem HRIS (sistem informasi sumber daya manusia) terbaik yang memiliki banyak fungsi SDM otomatis ke dalam satu sistem
- APlikasi yang dapat memusatkan data karyawan dengan mengizinkan hanya satu orang yang berwenang untuk mengakses
  (tingkat kemanan tinggi).
- Modul kehadiran memantau waktu karyawan berdasarkan informasi tentang penyisipan dan perforasi.
- Antarmuka software lebih modern daripada yang lain
- Memiliki fitur unggulan seperti leave management, tracking waktu dan kehadiran, informasi karyawan, serta upload dokumen sekaligus download report dalam format CSV.

# Kekurangan
- Karena sasaran utama adalah usaha kecil dan menengah, software ini bukan yang terbaik untuk berfungsi maksimal di perusahaan besar

# Perbangingan dengan aplikasi lainnya
IceHrm dapat menggunakan satu sistem  perangkat lunak untuk semua fungsi HRM, karena perangkat lunak HRM lainnya dirancang untuk fungsi HRM tertentu secara terpisah.

IceHrm memiliki pilihan tiga edisi dengan setiap edisi memiliki fitur berbeda. sesuai kebutuhan SDM organisasi masing - masing atau berdasarkan jumlah karyawan di organisasi.
