# TCCtugas3

Login ke github kemudian  fork repo yang akan dijadikan proyek bersama (repo upstream).

Masuk ke git bash kemudian lakukan clone dengan cara 
`git clone https://github.com/alimuamar11/TCCtugas3.git`

Hubungkan repo lokal dengan repo upstream dengan cara mengetikkan di terminal :
`git remote add upstream https://github.com/amarGorsky/TCCtugas3.git`

membuat branch baru dengan perintah 
`git checkout -b amarGorsky`
kemudian memasukan kode program.

Add ke local kemudian commit kode yang telah di edit dengan mengetikan perintah sebagai berikut :
`git add -A`
`git commit -m “commit”`

Kemudian push branch kita tadi ke repo origin dengan cara :
`git push origin amarGorsky`

Buka repository di github, lalu klik New Pull Request dan pilih opsi base fork ke master dan head form ke amarGorsky.

Isikan keterangan lalu klik Create Pull Request dan tunggu Pull Request di Merge oleh upstream.

Setelah di merge oleh upstream, pastikan branch yang berisikan commit yang telah di merge oleh upstream dihapus di github dan repo lokal.
