
# Project Title

Kode di atas adalah contoh penggunaan OpenCV dan Matplotlib dalam pemrosesan gambar. Berikut adalah penjelasan dari setiap fungsi yang digunakan:

1. Membaca Gambar: Menggunakan `cv2.imread` untuk membaca gambar dari path yang diberikan.
   
2. **Menampilkan Gambar**: Fungsi `show_image` untuk menampilkan gambar menggunakan Matplotlib setelah mengonversi dari BGR ke RGB.

3. Rotasi Gambar: Menggunakan `cv2.getRotationMatrix2D` untuk mendapatkan matriks rotasi dan `cv2.warpAffine` untuk melakukan rotasi gambar.

4. Resize Gambar: `cv2.resize` digunakan untuk meresize gambar dengan faktor skala tertentu.

5. Crop Gambar: Fungsi `crop_image` untuk memotong gambar berdasarkan koordinat awal (start_x, start_y) dan dimensi (width, height).

6. Flip Gambar: `cv2.flip` untuk melakukan flipping (vertikal, horizontal, atau keduanya).

7. Translasi Gambar: Menggunakan `cv2.warpAffine` dengan matriks translasi untuk menggeser gambar sepanjang sumbu x dan y.

Setiap fungsi di atas mengambil gambar sebagai input dan mengembalikan hasil pemrosesan yang sesuai, yang kemudian ditampilkan menggunakan Matplotlib.
