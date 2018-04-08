# Deskripsi Git #
## Version Control System ##
Version control adalah sebuah sistem yang mencatat setiap perubahan terhadap sebuah berkas atau kumpulan berkas sehingga pada suatu saat anda dapat kembali kepada salah satu versi dari berkas tersebut.

Ada tiga macam jenis VCS yaitu :
* VCS Local
* VCS Terpusat
* VCS Terdistribusi

## GIT ##
Git adalah salah satu jenis Version Control System. Namun Git berbeda dengan VCS lainnya. Salah satu perbedaan yang mencolok antar Git dengan VCS lain yaitu dalam hal cara git memperlakukan datanya. VCS lain menyimpan informasi sebagai sebuah daftar perubahan berkas. Git memperlakukan datanya sebagai sebuah kumpulan snapshot dari sebuah miniatur sistem berkas.

Git memiliki 3 keadaan utama dimana berkas anda dapat berada: '''committed, modified dan staged'''. Committed berarti data telah tersimpan secara aman pada basisdata lokal. Modified berarti anda telah melakukan perubahan pada berkas namun anda belum melakukan commit pada basisdata. Staged berarti anda telah menandai berkas yang telah diubah pada versi yang sedang berlangsung untuk kemudian dilakukan commit.

Alur kerja dasar Git adalah seperti ini:

* Anda mengubah berkas dalam direktori kerja anda.
* Anda membawa berkas ke stage, menambahkan snapshotnya ke staging area.
* Anda melakukan commit, yang mengambil berkas seperti yang ada di staging area dan menyimpan snapshotnya secara permanen ke direktori Git anda.

Referensi : 
* https://git-scm.com/book/id/v1/Memulai-Git-Tentang-Version-Control
* https://git-scm.com/book/id/v1/Memulai-Git-Dasar-Git
