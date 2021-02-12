# Pengingat Command Git

```bash
git init ==> merubah folder jadi repository
```
```bash
git add .==> menambahkan semua file ke staging area
```
```bash
git commit -m "comment" ==> commit
```
```bash
git log -- nama file ==> lihat log perubahan
```
```bash
git checkout 5hashpertama -- namafilenya ==> checkout ke commit  bisa spesifik file yang dihapus/dirubah

```
```bash
git status ==> lihat status direktori
```
```bash
git commit -am "comment" ==> add sekalian commit
```
```bash
git branch ==> menampilkan list branch, warna hijau menunjukan branch sedang aktif
```
```bash
git branch namebranch ==> membuat branch baru
```
```bash
git log --all --decorate --oneline --graph ==> melihat graph
```
```bash
alias graph="git log --all --decorate --oneline --graph" ==> membuat graph command tidak kepanjangan
```
```bash
git checkout namabranch ==> selain pindah commit, command ini juga digunakan untuk pindah branch
```
ADA 2 JENIS MERGE (JANGAN LUPA HEADNYA PINDAH KE MASTER DULU)
FAST FORWARD, CABANG NYA CUMA 1 HOPE
DAN THREE WAY MERGE, CABANG NYA LEBIH DARI 1 HOPE
```bash
git merge namabrachygmaudimergekan ==> cara merge
```
```bash
git branch --merged ==> melihat branch2 yang sudah dimerge
```
```bash
git branch -d namabranch ==> hapus branch
```


```bash
kosong
```
Bikin Nama, nanti nama ini yang akan muncul saat ngepush di remote
```bash
git config --global/local user.email "gemaadhan@gmail.com"
git config --global/local user.name "gemaadhan"
git config --global/local --unset-all user.name
git config --global/local --unset-all user.email

```
