# #6 GIT BRANCH & MERGE

## RINGKASAN
### Branch
Untuk melihat branch yang tersedia, gunakan command berikut,
```sh
$ git branch
```
Tambah branch dengan command berikut,
```sh
$ git branch <nama branch>
```
Ganti branch yang sedang dimodifikasi dengan command berikut,
```sh
$ git chekout <nama branch>
```
Untuk melihat kronologis perubahan pada branch, gunakan command berikut,
```sh
$ git log
```
Untuk melihat grafik alur branches, gunakan command berikut,
```sh
$ git log --decorate --all --oneline --graph
```
Untuk menghapus branch tertentu, gunakan command berikut,
```sh
$ git branch -d <nama branch>
```

<p>&nbsp;</p>

### Merge
Ada dua tipe merge:
- Fast Forward - ketika branch yang dimerge sejalur dengan branch yang lainnya
- Three-way Merge - ketika branch di-merge dengan branch yang berbeda alur

Untuk _merge_ suatu branch, atur salah satu branch yang akan dimerge sebagai kepala branch. Lalu merge branches dengan command berikut,
```sh
$ git merge <target branch>
```
Untuk melihat branches yang sudah di-merge, gunakan command berikut,
```
$ git branch --merged
```

<p>&nbsp;</p>

<a style='display: block; text-align: right;' href="https://youtu.be/EGl7KxVOyNs">source</a>