# Proyek Akhir Pemrograman Berbasis Objek 1

Proyek ini adalah contoh sederhana aplikasi manajemen buku perpustakaan menggunakan Java sebagai tugas akhir dari mata kuliah Pemrograman Berbasis Objek 1.
## Deskripsi

Aplikasi ini memungkinkan pengguna untuk:

Menambahkan buku fisik maupun digital,

Menampilkan semua koleksi buku,

Mencari buku berdasarkan genre.

Program ini dibuat menggunakan bahasa Java dan dijalankan melalui console.
Aplikasi ini mengimplementasikan berbagai konsep penting dalam pemrograman berorientasi objek (OOP) seperti:
Class, Object, Atribut, Constructor, Mutator, Accessor, Encapsulation, Inheritance, Polymorphism, Seleksi, Perulangan, IO Sederhana, Array, dan Error Handling.

## Penjelasan Kode

Berikut adalah bagian kode yang relevan dengan konsep OOP yang dijelaskan:

1. **Class** adalah Template dasar objek. Terdapat tiga class:

```bash
public class Buku { ... }
public class BukuDigital extends Buku { ... }
public class Main { ... }
```

2. **Object** dibuat dari class, seperti:

```bash
koleksi[jumlah] = new Buku(judul, penulis, genre, tahun);
```

3. **Atribut** adalah Variabel dalam class, contohnya:

```bash
private String judul;
private String penulis;
```

4. **Constructor** adalah Method yang otomatis dipanggil saat object dibuat:

```bash
public Buku(String judul, String penulis, String genre, int tahun) { ... }
```

5. **Mutator** Method untuk mengatur nilai atribut:

```bash
public void setJudul(String judul) { ... }
```

6. **Accessor** Method untuk mengambil nilai atribut:

```bash
public String getJudul() { ... }
```

7. **Encapsulation** Atribut dibuat private, dan hanya dapat diakses melalui getter/setter:

```bash
private String genre;
public String getGenre() { return genre; }
```

8. **Inheritance** Class BukuDigital mewarisi dari class Buku:

```bash
public class BukuDigital extends Buku { ... }
```

9. **Polymorphism** Method tampilkanInfo() di-override pada class turunan:

```bash
if (pilihan == 1 || pilihan == 2) { ... }
```

11. **Perulangan** Perulangan untuk menu dan penampilan data:

```bash
while (true) { ... }
for (int i = 0; i < jumlah; i++) { ... }
```

12. **Input Output Sederhana** Menggunakan Scanner untuk input dan System.out.println untuk output:

```bash
Scanner input = new Scanner(System.in);
System.out.print("Judul: ");
```

13. **Array** Digunakan untuk menyimpan banyak buku:

```bash
Buku[] koleksi = new Buku[10];
```

14. **Error Handling** Untuk menangani kesalahan input:

```bash
try {
   ...
} catch (Exception e) {
   System.out.println("Terjadi kesalahan input");
}
```

## Usulan nilai

| No  | Materi         |  Nilai  |
| :-: | -------------- | :-----: |
|  1  | Class          |    5    |
|  2  | Object         |    5    |
|  3  | Atribut        |    5    |
|  4  | Constructor    |    5    |
|  5  | Mutator        |    5    |
|  6  | Accessor       |    5    |
|  7  | Encapsulation  |    5    |
|  8  | Inheritance    |    5    |
|  9  | Polymorphism   |   10    |
| 10  | Seleksi        |    5    |
| 11  | Perulangan     |    5    |
| 12  | IO Sederhana   |   10    |
| 13  | Array          |   15    |
| 14  | Error Handling |   15    |
|     | **TOTAL**      | **100** |

## Pembuat

Nama: Rais khazim
NPM: 2310010082
