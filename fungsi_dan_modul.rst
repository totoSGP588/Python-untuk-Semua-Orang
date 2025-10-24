Fungsi dan Modul
================

Fungsi
------
Fungsi digunakan untuk mengelompokkan kode agar mudah dipakai ulang.

```
def sapa(nama):
    print("Halo,", nama)

sapa("Dina")
```

Modul
-----
Modul adalah file berisi fungsi-fungsi yang bisa diimpor.

Contoh menggunakan modul bawaan:
```
import math

print(math.sqrt(16))  # akar kuadrat
```

Membuat modul sendiri:
1. Buat file bernama `mymodule.py`
2. Isi dengan fungsi:
   ```
   def halo():
       print("Halo dari modul saya!")
   ```
3. Gunakan di file lain:
   ```
   import mymodule
   mymodule.halo()
   ```
