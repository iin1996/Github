# Github
## Bagaimana menggunakkan github

### Yang perlu dilakukan sekali saja untuk inisial github
	$git config --global user.email "email github"
	$git config --global user.name "nama akun github"

### Remote github
	$git remote add origin ...

### Clone repo yang akan di manage
	$git clone <url dari repo>

### Masuk kedalam folder yang telah diclone
	$cd NamaFolder

### Tambahkan file kedalam folder
    apa saja nama file atau foldernya 

### Tambahkan file kedalam git untuk di commit ,jika ingin menambahkan semua bisa dengan menggunakan peritah berikut
	$git add -A
### Jika tidak ingin menambahkan semua bisa memilih file yang akan ditambahkan dengan llangsung saja misalnya foder yang akan ditambahan adalah tugas 
    $git add tugas

### Commit (untuk menginisialisasi file yang akan di push)
	$git commit -m "...ini adalah pesan yang akan di sampaikan..."

### Push kedalam repo
	$git push origin master
	:: origin adalah letak url nya
	:: dan master adalah nama branch nya

## Jika Bekerja Secara Tim
    mungkin bekerja secara tim hampir sama dengan perintah diawal yang membedakan disini adalah langkah pertama :
    1. memilih siapa yang akan menjadi upstream 
    2. kemudian fork upstream 
    3.setelah itu clone 
### Untuk mengetahui perubahan repo
	$git clone

## Istilah-Istilah github
	### upstream
	### fork
	### branches sama dengan cabang- cabang 
	### pull request
	### clone

	" branch paling banyak berguna jika kita melakukan kolaborasi"

## Label pada saat membuat issues

	- bug > masalah
	- enhancement > perlu diperbaiki
	- help wanted > butuh bantuan jika team tidak sanggup memperbaikinya
	- wontfix > tidak perlu diperbaiki
