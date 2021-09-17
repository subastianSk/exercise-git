1.git init . #initialisasi existing project
git init skilvul #inisialisasi

git remote add [name-origin] [link-https]

git add . #seluruh file yang mengalami perubahan dikirim kondisi stage
git add index.html #file html yang mengalami perubahan dan dikirimkan ke kondisi stage

git commit -m "[Message]" #Memberikan informasi perubahan untuk developer

git push -u [name-origin] [name-branch] #master/main

2.Perintah git reset sering disebut sebagai perintah berbahaya yang dapat menghancurkan catatan hsitori.
Perintah ini memiliki tiga argumen atau opsi utama, yaitu --soft, --mixed, dan --hard.

```- soft akan mengebalikan dengan kondisi file dalam keadaan staged
   - soft akan mengebalikan dengan kondisi file dalam keadaan staged
   - mixed akan mengebalikan dengan kondisi file dalam keadaan modified
  - hard akan mengebalikan dengan kondisi file dalam keadaan commited
```
Coba periksa catatan perubahan dengan perintah git log, pasti ada yang hilang dan kita tidak akan bisa kembali lagi
Revert artinya mengembalikan. Perintah ini lebih aman daripada git reset, karena tidak akan menghapus catatan histori.

Revert akan akan mengambil kondisi file yang ada histori, kemudian menggabungkannya dengan commit terakhir.

3.Git merupakan alat Version Control System. GitHub merupakan alat version control sekaligus penyimpanan cloud
