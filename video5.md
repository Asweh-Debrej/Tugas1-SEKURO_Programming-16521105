# #5 BEKERJA DENGAN GIT

## RINGKASAN
GIT memiliki 3 area :
1. Working Tree - area di mana pengguna menyimpan file yang akan diproses.
2. Staging Area - di sini repo akan dipantau dan diproses perubahannya hingga menjadi siap disimpan perubahannya.
3. History - area penyimpanan perubahan repo secara kronologis.

<p>&nbsp;</p>

Panduan menggunakan GIT:

### Instalasi GIT
1. Install GIT yang terdapat di  <a style='text-align: right;' href="https://git-scm.com/downloads">website GIT</a>.
2. Buka _installer_ dan atur konfigurasi awal program GIT lalu _install_ GIT.

<p>&nbsp;</p>

### Command Dasar GIT
- $ git init - menginisialisasi repo GIT
- $ git add <file(s)> - menambahkan file ke staging area
- $ git status - menampilkan status perubahan
- $ git commit - membuat perubahan
- $ git branch - membuat branch
- $ git chekout - menyetel suatu branch sebagai master
- $ git help - menampilkan list command lainnya
- $ git ...

<p>&nbsp;</p>

### Commit Dengan GIT
1. Buka GIT bash
2. Buka _directory_ proyek dalam GIT bash dengan mengetik
```sh
$ cd <directory>
```
3. Inisialisasikan GIT dalam folder tersebut
```sh
$ git init
```
4. Buatlah perubahan dalam direktori tersebut. Tambahkan beberapa file, lalu commit perubahannya
```sh
$ git commit -am <komentar>
```

<p>&nbsp;</p>

<a style='display: block; text-align: right;' href="https://youtu.be/e-6OkXRqWaE">source</a>