# KOLABORASI PADA GIT

**PERSIAPAN KOLABORASI SISI CREATOR**

Setelah membuat repository pada repository github, creator bisa mengundang orang lain untuk berkolaborasi(collaborator), Collaborator bisa kita tambahkan melalui web github dengan cara :
-	Pada repository yang sebelumnya kita buat, kita masuk Settings
-	Pilih Collaborator
-	Kemudian di sana ada isian , kita bisa memasukkan username git, nama ataupun email address.
-	Kemudian tinggal Click Add collaborator
-	Pembuat repository kemudian akan menunggu username atau collaborator untuk Accept
-	Link invite biasanya dikirim ke email collaborator atau kita bisa memberikan link invite ke
collaborator , biasanya linknya adalah : https://github.com/user_pembuat_repo/nama_repo/invitations

**PERSIAPAN KOLABORASI SISI COLLABORATOR**

Kemudian dari collaborator kita buat brach agar tidak masuk ke master, dan nanti muncul Pull Request di creator repository dengan syntax :

```
git checkout -b <nama_branch>
```

Contoh kita buat cabanf dengan nama kolaborasi, maka syntaxnya adalah :

```
git checkout -b kolaborasi
```

Kita lakukan inisialisasi git dan lakukan push ke branch kita, jangan ke master dengan syntax :

```
git push origin kolaborasi
```
**MERGE**
Pada sisi creator, branch ini bisa kita merge ke master dengan syntax :

```
git merge <branch>
```

**KONFLIK SAAT MERGE**

Penggabungan pada github dilakukan secara otomatis, kadang terjadi konflik sehingga creator secara manual dharus melakukan edit berkas yang ditunjukkan oleh git. Kemudian kita bisa lakukan perubahan dengan syntax :

```
git add <namaberkas>
```

sebelum dilakukan merge, kita bisa melakukan preview menggunakan

```
git diff <branch_asal> <branch_tujuan>
```