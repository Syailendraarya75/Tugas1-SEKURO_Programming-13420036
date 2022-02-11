# Rangkuman Video 12

<p>&nbsp;</p>

## Oleh
### Nama : Syailendra Arya Daniswara
### NIM  : 13420036

<p>&nbsp;</p>

## GITIGNORE

<p>&nbsp;</p>

### link video : https://www.youtube.com/watch?v=LK3kX4n-vLM&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=12

<p>&nbsp;</p>

Gitignore merupakan sebuah file yang dapat disimpan pada repository git agar kedepannya saat melakukan add dan commit ada file yang tidak ikut terbawa. 
Contohnya ketika tidak ingin file sistem di computer terbawa.

- Cara untuk membuat folder di git tanpa harus buat manual seperti ini:
```
$ mkdir nama_folder
```

- Cara Untuk membuka visual studio code di folder git
```
$ code .
```
- Untuk menghubungkan git dan githun copy code remote pada github lalu paste pada command git
$ git remote add origin https://github.com/Syailendraarya75/coba_gtitgnore.git

Contoh commandnya sebagai berikut:

![Screenshot 2022-02-10 205211](https://user-images.githubusercontent.com/91923106/153530785-bc871cd2-7689-4609-81a6-e0d6ca9e8fa9.png)

- Untuk menghubungkan repo git ke github
```
$ git push -u origin master
```
![Screenshot 2022-02-10 210453](https://user-images.githubusercontent.com/91923106/153530906-fc25d015-ecb7-4c96-8f1e-7180b8fae0ce.png)

- Jika ingin menambahkan file tertentu pada staging area, buat file .gitignore pada vs code, 
lalu pada file .gitignore tulis nama file yang tidak ingin dimasukkan ke staging area. Selain file di gitignore juga dapat menyimpan folder atau sebuah pola seperti 
contoh jika tidak ingin file exe Maka ketik “*.exe”.

### Untuk mencari file apa saja yang sebaiknya masuk gitignore
-	Github.com/github/gitignore
-	Gitignore.io



