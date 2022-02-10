# Rangkuman Video 5

<p>&nbsp;</p>

## Oleh
### Nama : Syailendra Arya Daniswara
### NIM  : 13420036

## BEKERJA DENGAN GIT

<p>&nbsp;</p>

### link video : https://www.youtube.com/watch?v=e-6OkXRqWaE&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=5

<p>&nbsp;</p>

Contoh Git Command

<p>&nbsp;</p>

1.Untuk menginisialisaso repo git
```
$ git init
```

2. Menambahkan file ke yang disebut staging area
```
$ git add <file(s)>
```

3. Untuk mengetahui status repo
```
$ git status
```

4. Untuk melakukan commit
```
$ git commit
```

5. Untuk menambah konfigurasi ke dalam git
```
$ git config
```

6. Untuk membuat branch
```
$ git branch
```

7. Untuk mencari tahu cara memakia sebuah perintah
```
$ git help
```



Jika sudah membuat repo di Git terdapat 3 area yaiut
-	Working tree = folder tempat bekerja
-	Staging area =  memberitahu git bahwa terjadi perubahan
-	History 
History dan staging area akan tersimpan  dalam sebuah folder Bernama .git
Jika sudah membuat folder git akan memantau folder jika terjadi perubahan dari working tree akan berpindah ke staging area dengan commad  $ git add, lalu jika sudah oke dapat di commit dengan command $ git commit untuk memindahkan ke history.
Untuk menyimpan suatu file didalam stating area digunakan command git add pada file yang telah ada difolder tetapi tidak ditrack oleh git. Hal ini karena pada saat mensave source di vscode itu tidak bisa membuat file bisa dicommit sehingga track dari file tersebut tidak dapat dibaca.
jika file sudah masuk ke staging area file dapat di commit dengan command commit tetapi pertama harus memberitahu data dengan git config. Jika saat melakukan command git commit  masuk ke kode editor vim cukup tekan esc, lalu tulis :q

Command

<p>&nbsp;</p>

-	Untuk Mengetahui directory
```
$ pwd
```
![Screenshot 2022-02-10 075923](https://user-images.githubusercontent.com/91923106/153508091-b0e7dce7-af8a-42ad-9691-a832e3d92e76.png)

- Untuk menampilkan info bagaimana cara meggunakan git
```
$ git
```
![Git di git bash](https://user-images.githubusercontent.com/91923106/153508332-19abb065-b380-40af-ab5e-5b79577328e8.png)

- Untuk menghilangkan isi terminalnya
```
$ clear
```
![Screenshot 2022-02-10 074608](https://user-images.githubusercontent.com/91923106/153508557-5031b49e-3950-48bb-9564-286a51968749.png)

- Untuk memperlihatkan git apa dan versi apa
```
$ git –-version
```
![Screenshot 2022-02-10 074739](https://user-images.githubusercontent.com/91923106/153508759-f9100f78-3375-436f-9df5-f8b162b1c122.png)

- untuk memperlihatkan file dan folder apa saja
```
$ ls
```
![Screenshot 2022-02-10 080516](https://user-images.githubusercontent.com/91923106/153508922-5ea6cc68-340c-45cd-936b-413ead100d5f.png)

- untuk mengubah tempat directory
```
$ cd <nama directory>
```
![Screenshot 2022-02-10 080808](https://user-images.githubusercontent.com/91923106/153509066-3b8336c9-c2ce-45e2-9d8e-139606422491.png)

- untuk mengubah folder menjadi repo, maka folder menjadi repo git dengan branch master
```
$ git init
```
![Screenshot 2022-02-10 081151](https://user-images.githubusercontent.com/91923106/153509287-301bb833-98de-4dae-8f61-2b5fde792dcc.png)

- untuk memberitahukan informasi branch dan file didalam folder.
```
$ git status
```
![Screenshot 2022-02-10 174752](https://user-images.githubusercontent.com/91923106/153509448-39d55d99-cce2-4726-9caa-2dee48a86063.png)

- untuk memindahkan file ke staging area
```
$ git add <nama file>
```
![Screenshot 2022-02-10 175457](https://user-images.githubusercontent.com/91923106/153509635-347699b1-fdaa-4e6e-97e1-406a33024e61.png)

- untuk melakukan commit pada folder git
```
$ git commit
```
![Screenshot 2022-02-10 175947](https://user-images.githubusercontent.com/91923106/153509769-b38d3348-b908-4741-9afc-e38d57a02b60.png)

- untuk menkonfigurasi nama dan email user yang melakukan commit
```
$ git config --global user.email "you@example.com"
```
```
$ git config --global user.name "your name"
```
![Screenshot 2022-02-10 180524](https://user-images.githubusercontent.com/91923106/153510076-3cdf7cd1-fa46-4652-b015-7fad76372f12.png)

- untuk me-commit file dengan message
```
$ git commit -m "message"
```
![Screenshot 2022-02-10 181205](https://user-images.githubusercontent.com/91923106/153510222-d9631b60-26f5-408f-850d-1a976f7e927b.png)

- untuk memindahkan file ke staging area dan memodify file yang telah diedit (note= dapat dilakukan di lebih dari 1 file)
```
$ git add .
```
![Screenshot 2022-02-10 182259](https://user-images.githubusercontent.com/91923106/153510532-99c82ed0-cda9-4dd8-bed4-79aed70a7dab.png)

- untuk melihat commit apa saja yang dilakukan (note =git log – nama file untuk command file tertentu)
```
$ git log
```
![Screenshot 2022-02-10 182829](https://user-images.githubusercontent.com/91923106/153510595-87068c2b-78c2-47eb-9d58-71d2d36885ce.png)

- untuk mengembalikan file yang dihapus
```
$ git checkout
```





