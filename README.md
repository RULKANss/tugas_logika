# tugas_logika
## input kode 
```
# Nomer 1
p = True
q = False
hasil_1 = p or not q
print(f"Soal 1: {hasil_1}")

# Nomer 2
p = True
q = False
hasil_2 = p and q
print(f"Soal 2: {hasil_2}")

# Nomer 3
p = False
q = True
hasil_3 = (not p) or q
print(f"Soal 3: {hasil_3}")

# Nomer 4
p = True
hasil_4 = not p
print(f"Soal 4: {hasil_4}")

# Nomer 5
p = True
q = False
r = True
hasil_5 = p <= (q or r)
print(f"Soal 5: {hasil_5}")

# Nomer 6
p = True
q = True
hasil_6 = (not p) and q
print(f"Soal 6: {hasil_6}")
```

### output kode
```
PS C:\puasa> & C:/Users/Syahrul/AppData/Local/Microsoft/WindowsApps/python3.11.exe c:/puasa/tugas.py
Soal 1: True
Soal 2: False
Soal 3: True
Soal 4: False
Soal 5: True
Soal 6: False
PS C:\puasa>
```
### kesimpulan
- Disjungsi dan Negasi: Jika salah satu pernyataan benar, maka hasilnya True.

- Konjungsi: Harus kedua-duanya benar untuk menghasilkan True, jika ada yang salah maka hasilnya False.

- Implikasi: Jika premis pertama salah, maka hasil selalu True. Jika premis pertama benar, maka bergantung pada premis kedua.

- Negasi: Membalik nilai kebenaran, jika True maka False, dan sebaliknya.

- Gabungan Disjungsi dan Implikasi: Disjungsi dalam implikasi tetap mengikuti aturan implikasi dasar.

- Konjungsi dan Negasi: Jika salah satu bernilai False, maka hasil konjungsi selalu False.
