# Komunikasi Data dan Jaringan Komputer
## Kelompok 9
~ Daffa fikri
~ Dzakiyyah Hasbi
~ Maya Amelia

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

# Screenshoot
![2](https://user-images.githubusercontent.com/91837561/196994888-a8fa7902-0c4e-44f8-a77a-9691bfbc3e8b.png)
![3](https://user-images.githubusercontent.com/91837561/196994926-5e2499dc-f463-41be-b1a7-5b67582d995b.png)
![4](https://user-images.githubusercontent.com/91837561/196995044-2b375077-dd04-4053-ab38-3ecbef34135c.png)
![5](https://user-images.githubusercontent.com/91837561/196995205-6c97026b-484f-42b7-a886-8f82bdc9c4b5.png)
![6](https://user-images.githubusercontent.com/91837561/196995097-1aec750b-f92c-4a75-a6e2-b1b91a92fce5.png)
![5](https://user-images.githubusercontent.com/91837561/196995244-58846f85-804c-4950-b992-41e174b86bfe.png)
![9](https://user-images.githubusercontent.com/91837561/196995275-609f3429-8db6-4a79-80f0-81bfd429b514.png)

