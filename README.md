# praktikum3
![gambar1](screenshoot/ss1.png)
# Penggunaan perintah end pada phyton Dengan Mengetikan
for i in range(5):
    print("Hello", end=" ")
# Hasil Eksekusi
![gambar2](screenshoot/ss2.png)
Perintah "end" digunakan untuk menentukan karakter yang akan ditambahkan setelah teks yang dicetak. Contoh di atas saya menentukan " " (spasi) sebagai karakter yang akan ditambahkan setelah setiap "Hello". Jika tidak menggunakan "end", maka setiap "Hello" akan dicetak pada baris baru.
# Penggunaan perintah sep pada phyton Dengan Mengetikan
![gambar3](screenshoot/ss3.png)
Angka = ["1", "2", "3", "4", "5"]
*menggunakan sep untuk menambahkan koma sebagai pemisah
print(*Angka, sep=", ")
# Hasil Eksekusi
![gambar4](screenshoot/ss4.png)
Perintah "sep" digunakan untuk menentukan karakter yang akan ditambahkan sebagai pemisah antar item dalam daftar. Dalam contoh di atas, saya menentukan ", " (koma dan spasi) sebagai pemisah antar item dalam daftar "Angka". Jika tidak menggunakan "sep", maka setiap item akan dicetak pada baris baru.
# Menginput variabel agar dapat dijumlahkan dengan mengetikkan
![gambar5](screenshoot/ss5.png)
angka1 = input("Masukkan angka pertama: ")
angka2 = input("Masukkan angka kedua: ")
operasi = input("Masukkan operasi (+, -, *, /): ")

angka1, angka2 = int(angka1), int(angka2)
if operasi == "+":
    hasil = angka1 + angka2
    print("Hasil penjumlahan: ", hasil)
elif operasi == "-":
    hasil = angka1 - angka2
    print("Hasil pengurangan: ", hasil)
elif operasi == "*":
    hasil = angka1 * angka2
    print("Hasil perkalian: ", hasil)
elif operasi == "/":
    if angka2 == 0:
        print("Tidak bisa melakukan pembagian dengan angka 0")
    else:
        hasil = angka1 / angka2
        print("Hasil pembagian: ", hasil)
else:
    print("Operasi yang dimasukkan salah")
# Hasil Eksekusi
![gambar6](screenshoot/ss6.png)