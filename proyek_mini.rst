Proyek Mini: Kalkulator Sederhana
=================================

Sekarang kita buat proyek mini menggunakan Python.

```
print("=== Kalkulator Sederhana ===")
a = float(input("Masukkan angka pertama: "))
b = float(input("Masukkan angka kedua: "))
operator = input("Pilih operator (+, -, *, /): ")

if operator == "+":
    hasil = a + b
elif operator == "-":
    hasil = a - b
elif operator == "*":
    hasil = a * b
elif operator == "/":
    hasil = a / b
else:
    hasil = "Operator tidak dikenal"

print("Hasil:", hasil)
```

Penjelasan:
- Menggunakan input untuk membaca nilai dari pengguna.
- Menggunakan kondisi `if` untuk memilih operasi.
- Cocok untuk latihan logika dasar Python.
