# doscom-sharing-github

## Instal Git di linux

``` 
sudo apt install git 
```

### Atau

``` 
sudo apt-get install git
```

### Setelah itu, coba perika versi yang terinstal dengan perintah:

```
git --version
```
### maka nanti akan muncul output seperti ini

```
git version 2.17.1 (tergantung versi kalian)
```



##  Konfigurasi Awal yang Harus dilakukan setelah menginstal git

### Ada beberapa konfigurasi yang harus dupersiapakan sebelum mulai menggunakan Git, seperti name dan email. Silahkan lakukan konfigurasi dengan perintah berikut ini

```
git config --global user.name "namakamu"
git config --global user.email contoh@gmail.com
``` 
### Kemudian periksa konfigurasinya dengan perintah:

```
git config --list
```

### Apabila berhasil tampil seperti gambar berikut ini, berarti konfigurasi berhasil

```
user.name=namakamu
user.email=contoh@gmail.com
```
#### Usahakan nama dan email sama dengan akun github mu agar mudah diintegrasikan




## Menginisialisasi git pada project

#### masuk kedalam folder projectmu dan ketikkan

```
git init
```
## Menambah record git 

#### Jika Sudah melakukan inisialisasi dan file projectmu siap di upload , kemudian ketikkkan

```
git add <nama file> ///menambah file tertentu

git add . ///menambah semua filenya
```

## Mengcommit git

#### Jika Sudah melakukan penambahan record , kemudian kita beri pesan pada record yang sebelumnya kita tambahkan 

```
git commit -m "pesan anda"
```

## Melihat log atau daftar commit

#### Berguna untuk melihat riwayat file yang telah diupload

```
git log
```




## Hosting Project ke Github

### Menambahkan repo remote Repo remote adalah repo yang ada di luar komputer kita. Dalam contoh ini adalah repo di github

```
git remote add <nama-remote> <link-repo-remote>
``` 
#### Contoh :

```
git remote add origin https://github.com/DOSCOM/belajargithub.git
```

### Menyimpan proyek ke repo remote

```
git push <nama-remote> <nama-branch>
```
#### secara default branch yang dimiliki adalah master. Contoh :

```
git push origin master
```

