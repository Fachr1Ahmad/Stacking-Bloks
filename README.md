# STACKING BLOKS

# Nama Anggota Kelompok
No | Nama | NIM |
--- | --- | --- |
1 | Hizkia H J Naibaho      | 118140036 |
2 | Winda                   | 120140123 |
3 | Fachri Ahmad            | 120140124 |
4 | Dodi Sihombing          | 120140132 |
5 | Dandy Arkandhiya Putra  | 120140203 |
6 | Nabilla Putri Maharani  | 120140177 |

# Deskripsi Program
Stacking Bloks merupakan aplikasi game yang mana berupa permainan menyusun balok. Kita dituntut untuk menyusun balok yang mana balok akan habis  ketika terpenuhi satu baris. Stacking Bloks dijalankan dengan bahasa pemrograman python yang mana untuk menjalankannya kita menggunakan library py.game. Py.game sendiri merupakan sebuah modul gratis yang digunakan  dalam pengembangan sebuah game menggunakan bahasa python.

# Cara menjalankan Cotainer (Windows)
Untuk menjalankan container ada beberapa prerequisite: Install 2 software dibawah ini.
* Docker dekstop ([Download Here](https://docs.docker.com/desktop/windows/install/))
* VcXsrv Windows X server ([Download Here](https://sourceforge.net/projects/vcxsrv/))

1. Clone repository ini, masuk kedalam direktori 
2. Jalankan docker desktop, dan lakukan build image pada terminal dengan perintah
```
docker build -t main
```
3. Sambil menunggu build selesai, selanjutnya setup VcXsrv (X Launcher). Buka aplikasi XLauncher yang sudah diinstall. Pada window awal pilih Multiple Windows dengan display number -1 > next > Start no client > next > centang disable access control > next > finish. Atau juga dapat dilakukan dengan membuka file konfigurasi Xlauncher yang ada di repository ini yaitu file 'Docker.xlaunch'.
4. Setelah build Selesai jalankan container dengan perintah:
```
docker run --rm main
```
5. Container sudah berjalan dan game sudah dapat dimainkan

# Video Demo Container
Berikut akan ditampilkan video demo container.

