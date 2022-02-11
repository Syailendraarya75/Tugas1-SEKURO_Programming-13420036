# Rangkuman Video 6

<p>&nbsp;</p>

## Oleh
### Nama : Syailendra Arya Daniswara
### NIM  : 13420036

<p>&nbsp;</p>

## GIT BRANCH & MERGE

<p>&nbsp;</p>

### link video : https://www.youtube.com/watch?v=EGl7KxVOyNs&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=6

<p>&nbsp;</p>

### Cara lain untuk mengubah directory ke folder tertentu:
- Pertama, ketik command cd pada git bash lalu Tarik folder yang diinginkan
- Kedua, masuk ke dalam folder di library lalu klik kanan pada mouse lalu klik git bash here

<p>&nbsp;</p>


- Jika ingin langsung commit pada VS code gunakan command git commit -am “pesan” seperti ini:

```
$ git commit -am ”message”
```
![Screenshot 2022-02-10 194129](https://user-images.githubusercontent.com/91923106/153529178-1350fa44-6fd2-4db2-b416-93578d5df8a8.png)

- Implementasi Branch di GIT tidak sesederhana itu jika kita punya repo dan kita melakukan commit maka commit memiliki identifikasi berupa hash email dan timestamp, tetapi commit terhubung terhadap branch. Untuk mengetahui sebuah branch yang aktif terdapat head untuk mengetahui kita di branch mana.
Untuk menambah branch dapat digunakan command git branch nama file, atau jika ingin melihat branch apa saja yang dibuat dapat menggunakan git branch saja
```
$ git branch nama_branch
```
```
$ git branch
```
![Screenshot 2022-02-10 195023](https://user-images.githubusercontent.com/91923106/153529312-a5cfe155-d5d2-428b-8227-90acb7eb96e2.png)

- Command git log --all --decorate --oneline –graph digunakan untuk melihat data commit dan branch pada repo
```
$ git log --all --decorate --oneline –graph
```
![Screenshot 2022-02-10 195349](https://user-images.githubusercontent.com/91923106/153529532-8f6cb8d8-ba3d-4f6e-b9c6-6e415ded9a25.png)

- Untuk mengganti code pada git dapat digunakan alias seperti berikut
```
$ alias graph="git log --all --decorate --oneline --graph"
```
```
$ graph
```
![Screenshot 2022-02-10 195914](https://user-images.githubusercontent.com/91923106/153529662-0eb377f6-8722-49d9-8b40-64fb9e156cd6.png)

- Untuk mengganti branch lain untuk menjadi head dapat digunakan command checkout seperti berikut:
```
$ git checkout nama branch
```
![Screenshot 2022-02-10 200550](https://user-images.githubusercontent.com/91923106/153529749-8a7c7e2e-d3a5-4d0a-aeb4-b7d465fd624d.png)

Note= Jika kita pindah dari git master ke git cabang lalu membuat file baru di git cabang maka jika Kembali ke branch utama file  maka file dari branch cabang akan hilang.

<p>&nbsp;</p>

### Terdapat 2 jenis Merge
-	Fast Forward 
Terjadi ketika branch yang digabungkan terdapat di direct path
-	Three way merge
ketika menggabungkan barnch  dengan merge  akan memunculkan commit baru

<p>&nbsp;</p>

- Untuk merge branch pada git dapat digunakan command merge
```
$ git merge nama branch
```
![Screenshot 2022-02-10 202219](https://user-images.githubusercontent.com/91923106/153529975-9ffa40b7-b11b-4f10-9bbf-05876069a489.png)

Note= pastikan dulu branch headnya merupakan branch yang ingin di merge

- Untuk mengetahu branch yang sudah dimerged dapat digunakan
```
$ git branch –merged
```
![Screenshot 2022-02-10 202748](https://user-images.githubusercontent.com/91923106/153530083-0f0f6c50-df6d-4f1b-bd85-4733e5199463.png)

- Untuk menghapus branch command  seper ti ini
```
$ git branch -d <nama_branch>
```
![Screenshot 2022-02-10 202931](https://user-images.githubusercontent.com/91923106/153530135-207fc9d2-88ff-47d7-9c03-371262853dc9.png)

-	Jika branch belum di merged tapi ingin dihapus maka gunakan command
```
$ git branch -D nama_branch
```

- Jika menggunakan three way merge maka tinggal merge menggunakan command seperti sebelumnya, 
nanti akan membuka file di teks editor lalu save file tersebut agar command dapat berjalan

![Screenshot 2022-02-10 203740](https://user-images.githubusercontent.com/91923106/153530262-ab0988fa-c3ef-4194-855a-318e9d584010.png)










