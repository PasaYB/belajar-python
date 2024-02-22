# Swap Variabel
## Definisi 

Swap variabel dalam Python adalah proses pertukaran nilai antara dua variabel. Dalam beberapa bahasa pemrograman,
kita mungkin perlu menggunakan variabel tambahan atau operasi aritmatika untuk menukar nilai antara dua variabel. 
Namun, dalam Python, kita dapat menukar nilai dua variabel dengan cara yang lebih singkat dan langsung tanpa menggunakan variabel tambahan.


![cara kerja](https://media.geeksforgeeks.org/wp-content/uploads/20200110142212/python-swap-two-variable.png)

## Metode
### 1. Naive Approach

Metode pertama, yang disebut "Naive Approach", adalah dengan menyimpan nilai salah satu variabel (misalnya x) dalam sebuah variabel sementara, 
kemudian menetapkan variabel x dengan nilai variabel y. Terakhir, menetapkan variabel y dengan nilai variabel sementara.
```python
# Program Python untuk mendemonstrasikan
# pertukaran dua variabel
 
x = 10
y = 50
 
# Pertukaran dua variabel
# Menggunakan variabel ketiga sementara
temp = x
x = y
y = temp
 
print("Nilai x:", x)
print("Nilai y:", y)

```
### 2. Comma Operator
Metode kedua menggunakan operator koma (comma operator) untuk menukar nilai variabel tanpa menggunakan variabel sementara.
```python
# Program Python untuk mendemonstrasikan
# pertukaran dua variabel
 
x = 10
y = 50
 
# Pertukaran dua variabel 
# tanpa menggunakan variabel ketiga
x, y = y, x
 
print("Nilai x:", x)
print("Nilai y:", y)
```

Dalam kedua contoh tersebut, nilai variabel x dan y ditukar dengan menggunakan metode yang berbeda,
namun hasilnya sama.

## Referensi
- https://www.geeksforgeeks.org/python-program-to-swap-two-variables/
- https://www.programiz.com/python-programming/examples/swap-variables
