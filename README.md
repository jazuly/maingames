## 1. Soal Teori: Diagram Database Aplikasi rumah makan
### Saya akan menggunakan javascript karena lebih mudah untuk di maintenance.
## Gambar ERD
![ERD](/ERD.png)

## 2. Permainan Dadu
### Pada program ini sama mengabaikan kondisi
> Dadu angka 1 akan diberikan kepada pemain yang duduk disampingnya. Contoh, pemain pertama akan memberikan dadu angka 1 nya ke pemain kedua
### Karena kondisinya menurut saya ambigu, bagaimana kalau pemain hanya 3, dan saat `pemain3` mendapat angka 1 kemana angka 1 tersebut akan di berikan jika tidak ada `pemain4`?
### Pada contohnya juga ambigu, pada giliran pertama `pemain1` mendapat angka 1 dan di berikan ke `pemain2` tapi setelah di evaluasi `pemain1` masih memiliki angka 1 tersebut.
Untuk detail codingnya tersedia di file [diceGame.html](/diceGame.html "diceGame.html")
