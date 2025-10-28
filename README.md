**nama**maulana qodli zaka
**nim**43050230021
 Transformasi Gambar

 1. Translasi (Translation)

Translasi adalah proses **menggeser posisi gambar** ke arah tertentu (kanan, kiri, atas, atau bawah).
Transformasi ini dilakukan dengan fungsi `cv2.warpAffine()` dan matriks translasi.
**Hasilnya:** gambar pelukis digeser ke kanan dan sedikit ke bawah agar posisinya lebih seimbang.

 2. Rotasi (Rotation)

Rotasi digunakan untuk **memutar gambar** terhadap titik pusat dengan sudut tertentu.
Fungsi yang digunakan adalah `cv2.getRotationMatrix2D()` dan `cv2.warpAffine()`.
**Hasilnya:** karakter diputar sekitar **30°** untuk memberikan efek sedang menunduk saat melukis.

---

 3. Crop (Pemotongan Gambar)

Crop berfungsi untuk **memotong sebagian area gambar** agar fokus pada bagian penting.
Proses ini dilakukan dengan slicing array (`image[y1:y2, x1:x2]`).
**Hasilnya:** bagian wajah pelukis dipotong untuk menampilkan detail ekspresinya.
