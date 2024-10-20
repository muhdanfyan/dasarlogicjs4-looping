# Pengenalan Looping di JavaScript

Looping atau perulangan adalah salah satu bagian paling penting dalam pemrograman. Dengan menggunakan looping, kita dapat melakukan sesuatu berulang-ulang tanpa harus menulis kode yang sama berulang-ulang.

## Macam-macam Looping di JavaScript

Ada beberapa macam looping di JavaScript, yaitu:

### For Loop

For loop adalah salah satu jenis looping yang paling umum digunakan. For loop memungkinkan kita untuk melakukan sesuatu berulang-ulang dengan menggunakan variabel yang dideklarasikan di dalam for loop.

Contoh penggunaan for loop:
```
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```
### For In Loop

For in loop digunakan untuk mengulangi setiap properti yang ada di dalam objek.

Contoh penggunaan for in loop:
```
const person = {
    nama: 'John Doe',
    umur: 25,
    alamat: 'Jalan Jalan'
};

for (let key in person) {
    console.log(key + ': ' + person[key]);
}
```
### For Of Loop

For of loop digunakan untuk mengulangi setiap item yang ada di dalam array.

Contoh penggunaan for of loop:
```
const fruits = ['Apple', 'Banana', 'Orange'];

for (let fruit of fruits) {
    console.log(fruit);
}
```

### While Loop

While loop adalah salah satu jenis looping yang paling sederhana. While loop memungkinkan kita untuk melakukan sesuatu berulang-ulang selama kondisi yang diberikan terpenuhi.

Contoh penggunaan while loop:
```
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}
```

### Do While Loop

Do while loop mirip dengan while loop, tetapi do while loop akan melakukan sesuatu minimal sekali sebelum kondisi yang diberikan diperiksa.

Contoh penggunaan do while loop:
```
let i = 0;
do {
    console.log(i);
    i++;
} while (i < 5);
```

# Tugas Pemrograman JavaScript: Looping (Perulangan)

Selamat datang di tugas pemrograman JavaScript! Dalam tugas ini, kamu akan berlatih menggunakan **looping** atau **perulangan** untuk menyelesaikan beberapa soal di bawah ini. Setiap soal dirancang untuk mengasah logika dan pemahaman tentang perulangan dalam pemrograman.

## Tugas 1: Tampilkan Angka Berurutan
Buat sebuah program yang meminta pengguna untuk memasukkan **nilai awal** dan **nilai akhir** melalui prompt, kemudian tampilkan angka berurutan dari nilai awal hingga nilai akhir dalam satu baris, dipisahkan dengan spasi.

- **Contoh Input:**
  - Nilai Awal: 3
  - Nilai Akhir: 7
- **Output yang diharapkan:**
```
  - `3 4 5 6 7`
```
- **Instruksi:**
  - Gunakan **`for` loop** untuk menyelesaikan tugas ini.
  - Cetak angka berurutan dari **nilai awal** hingga **nilai akhir** di satu baris.

---

## Tugas 2: Tampilkan Pola Angka dengan "x"
Buat program yang menghasilkan pola angka dan huruf "x" secara bergantian. Untuk setiap angka ganjil, cetak angkanya. Untuk setiap angka genap, cetak "x".

- **Output yang diharapkan:**
```
1 x 3 x 5 x 7 x 8
```
markdown
Salin kode

- **Instruksi:**
- Gunakan **`for` loop** untuk mencetak angka dari 1 hingga 8.
- Jika angka tersebut ganjil, cetak angkanya.
- Jika angka tersebut genap, cetak `"x"`.

---

## Tugas 3: Buat Pola Persegi dari Karakter "*"
Buat program yang meminta pengguna untuk memasukkan sebuah angka melalui prompt, kemudian cetak persegi yang terdiri dari simbol bintang `"*"` dengan ukuran sesuai angka yang dimasukkan.

- **Contoh Input:**
- Masukkan Angka: 4
- **Output yang diharapkan:**

```
* * * * *
* * * * *       
* * * * *       
* * * * *
```
- **Contoh Input:**
- Masukkan Angka: 3
- **Output yang diharapkan:**

```
* * *
* * *
* * *
```

- **Instruksi:**
- Gunakan **`for` loop** bersarang (nested loop) untuk mencetak bintang dalam bentuk persegi sesuai angka yang dimasukkan pengguna.

---

## Tugas 4: Pondok Informatika (FizzBuzz)
Buat program yang mencetak angka dari 1 hingga jumlah yang dimasukkan oleh pengguna melalui prompt. Namun, jika angka tersebut:
- Kelipatan 3, cetak `"Pondok"`.
- Kelipatan 5, cetak `"Informatika"`.
- Kelipatan 3 dan 5 sekaligus, cetak `"FizzBuzz"`.

- **Contoh Output:**
- Jika pengguna memasukkan angka 15, hasil yang diharapkan:
 
  ```
  1
  2
  Pondok
  4
  Informatika
  Pondok
  7
  8
  Pondok
  Informatika
  11
  Pondok
  13
  14
  FizzBuzz
  ```

- **Instruksi:**
- Gunakan **`for` loop** untuk mencetak angka dari 1 hingga batas yang dimasukkan oleh pengguna.
- Gunakan **conditional statements** (if-else) untuk memeriksa apakah angka tersebut kelipatan 3, 5, atau 3 dan 5 sekaligus.

---

Selamat mengerjakan! Setelah selesai, silakan unggah solusi Anda ke repository ini untuk diperiksa.
Penjelasan Struktur Soal:
Tugas 1 (Tampilkan Angka Berurutan): Melatih pemahaman dasar for loop dan input dari pengguna.
Tugas 2 (Pola Angka dengan "x"): Mengasah logika dalam pengkondisian dan perulangan.
Tugas 3 (Pola Persegi): Melatih penggunaan loop bersarang (nested loop) untuk membentuk pola.
Tugas 4 (Pondok Informatika/FizzBuzz): Membangun logika pengkondisian untuk masalah klasik FizzBuzz dengan kombinasi looping dan kondisi.
Soal-soal ini dirancang agar peserta dapat mempraktikkan berbagai jenis perulangan sambil memperkuat pemahaman mereka tentang logika pemrograman.