# Apa itu Workflow? #

Workflow merupakan serangkaian cara kerja yang disepakati bersama untuk mencapai tujuan tertentu.
Git Workflow adalah kesepakatan dalam tata cara penggunaan Git dalam kolaborasi.
Ada banyak Workflow dalam Git baik yang terdokumentasi ataupun tidak.


Gitflow merupakan salah satu Workflow yang terdapat dalam Git.
Gitflow merupakan workflow central repository (satu repository yang berfungsi sebagai pusat komunikasi antara semua developer).
Jika menggunakan SourceTree maka Gitflow merupakan salah satu fitur didalamnya.

### Cabang Sejarah ###
GitFlow menggunakan dua cabang sebagai cabang sejarah yaitu cabang master dan develop.
Master merupakan cabang untuk sejarah rilis ofisial.
Umumnya setiap commit baru di Master diberi Tag versi.
Develop merupakan cabang untuk integrasi terhadap fitur-fitur.

### Cabang Fitur ###
Cabang fitur dibuat setiap kali ada fitur baru.
Cabang fitur dipecah dari cabang develop dan digabungkan kembali ke develop apabila sudah selesai.
Cabang fitur tidak boleh berhubungan dengan cabang master.
Setiap fitur baru memiliki satu cabang sendiri.

### Cabang Develop ###
Ketika cabang develop sudah memiliki banyak fitur maka cabang rilis akan dipecah dari cabang develop.
Dalam cabang develop hanya berisikan pembuatan dokumentasi, bug fixes, dan hal-hal lain untuk persiapan rilis.
Ketika sudah siap dirilis, cabang rilis akan digabungkan ke cabang master dan develop dan diberi tag versi.

### Cabang Hotfix ###
Cabang perbaikan (hotfix) digunakan secara cepat memperbaiki bug yang krusial di cabang master.
Cabang perbaikan dipecah dari cabang master dan digabungkan setelah selesai ke cabang master kembali.
Umumnya versi minor dari master akan bertambah setelah ada gabungan dari cabang perbaikan.

### Contoh GitFlow Workflow ###

Sebelum memulai buat cabang develop dari cabang master.

`$ git checkout develop`

Kemudian push ke origin

`$ git push -u origin develop`


### Referensi ###

https://bertzzie.com/knowledge/teknologi-kolaborasi/14-GitFlow.html
