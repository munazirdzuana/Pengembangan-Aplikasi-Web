# Materi Ajar 5 SD
https://youtu.be/csgX45PxuP8

-----------------------------------------------------------
# website RuangGuru honorer

## Permasalahan
- Berlandaskan dari lingkungan sekitar ada anak yang putus sekolah

## Rancangan Solusi
- Membuat aplikasi website ketika mengajar siapapun apapun bisa mendapatkan uang
- uang yang didapatkan berdasarkan waktu mengajar divalidasi oleh foto sebelum dan sesudah mengajar
-  
## Use Case
- user dapat mendaftar sebagai tutor
- tutor dapat memulai mengajar dengan mengisi form (nama Pelajaran, banyak peserta, foto, objek ajaran)
- sesudah mengajar tutor mengisi kembali form (foto setelah mengjar, foto yang membuktikan objek ajaran telah dicapai)
- tutor mendapatkan uang dari waktu dan banyak peserta yang diajar
- tutor dapat melihat pendapatan
- admin memvalidasi pendaftaran tutor
- admin memvalidasi foto foto sehingga tutor dapat mendapatkan uang

## Struktur Data

### tutor
no|Atribut|Tipe Data|Contoh
---|---|---|---
1|UUID|UUID4|1
2|NIK|String|3200127690****
3|Nama|String|munazir
4|E-mail|String|aku@gmaiiil.com
5|Pass|String|*******
6|desc|Text|seorang mahasiswa uin bdg
7|image|String|*foto propil
8|city|String|jl. doang kok
9|time|String|00:10:00
10|saldo|int|10.000
11|role|String|user


### kelas
Atribut|Tipe Data|Contoh
---|---|---
ID_kelas|Int|10
N_pelajaran|String|pelajaran membuat topeng
peserta|int|5
id_tutor|INT|1
obj|String|peserta dapat membuat topeng
foto|STRING|*foto mulai mengajar
point|INTEGER|00:10:00
Bukti|String|*foto, file

### Admin
Atribut|Tipe Data|Contoh
---|---|---
Id_admin|INT|00
Username|String|MunazOR
pass|Sting|*****
N_admin|Sting|Admin_1

## UX Wireframe
![WIreframe](https://user-images.githubusercontent.com/78277922/190235924-21759635-0039-433f-a5b2-8353317cb66e.jpg)
