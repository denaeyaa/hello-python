
## Variable
Secara sederhana, kita bisa anggap Variabel sebagai kata kata yang bernilai.
Dengan python, sangat mudah untuk mendefinisikan variabel dan memberikan nilainya. Bayangkan kamu ingtin menyimpan nomor 3 di variabel bernama "tiga"
```bash
tiga = 3
```
kamu baru saja menambahkan nilai 3 ke variabel 3

```bash
dua = 2
nomor = 343
```

dan kamu bisA tetapkan nilai lain apapun ke dalam variabel lain yang kamu buat atau kamu inginkan. Seperti yang kamu liat di contoh di atas, variabel "dua" menyimpan bilangan bulat 2, dan variabel "nomor" menyimpan 343.

Selain integer, kita juga bisa menggunakan boolean (True/False), string, float, dan masih banyak lagi tipe data lainnya.

## Tipe Data
### Numbers
Tipe data numbers ini memiliki 3 macam, yakni:

- Tipe data integer : Bilangan bulat positif atau negatif dan tidak memiliki angka desimal
  `contoh : 1 , -1`
- Tipe data Float : Bilangan riil yang dapat mewakili bilangan bulat atau bilangan desimal
  `contoh : 1,5 , 60.3`
- Tipe data Complex : Bilangan kompleks
  `1+2j`

### Boolean
Tipe data ini hanya bernilai TRUE atau FALSE.
Ada beberapa nilai yang baklal dianggap <i>false</i> sebagai berikut:
- Nilai yang memang sudah didefinisikan salah
- Angka nol dari semua tipe numerik
- Urutan dan Koleksi yang kosong

  contoh: `x = False` dan `x = True`
  
### String
  Variabel bernilai string diawali dengan single quote (' ')  atau double quote (" ")
  contoh: `'Naya'` atau `"x = Naya"`

  Kita bisa menggunakan tiga single quote atau double qoute untuk menyimpan string yang lebih dari satu baris `multi-line`
  contoh: 
  ```bash
  multi_line = """ Halo!
  Ayo kita lakukan yang terbaik,
  Sampai jumpa """
  ```

  Tetapi kita tidak bisa mengubah substring yang ada. Karena string dalam Python bersifat `immutable`
  ```bash
  x = "teman"
  x[0] = "f"
  ```

  Kita bisa menampilkan teks/string berdasarkan input dari pengguna dengan berbagai cara.
  1. Formatted String
  ```bash
  name = "denay"
  print(f"Hello, namaku {name}")
  ```

  2. % - Formatting
  ```bash
  name = "denay"
  print("namaku %s" % (name))
  ```

  3. str.format()
  ```bash
  name = "denay"
  print("namaku {}".format(name))
