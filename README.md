# Iftitah-Azzahrah-SDA
# Iftitah-Azzahrah Lego Ningtiyas
# G1A021014

#include <iostream>
Fungsi #include adalah sebuah prosesor pengarah yang mengatakan kepada kompiler untuk meletakan kode dari header file iostream kedalam program. Fungsi cout memerlukan file iostream.


using namespace std;
merupakan perintah yang dapat kita gunakan untuk menyajikan perintah atau deklarasi kepada sebuah aplikasi compiler yang menyatakan bahwa kita akan menggunakan seluruh berkas, class, atau fungsi yang Menjadi bagian dari sebuah namespace std yang bersangkutan. Berkat fungsi ini, kita dapat menghindari kesalahan berupa tidak dikenalnya cout yang ingin kita gunakan dari seluruh kombinasi maupun instruksi yang tersedia.


int main()
Maksud dari int di depan main adalah tipe data yang akan dikembalikan. Maka di dalam fungsi main(), wajib kita sertakan return 0. Artinya, fungsi main akan mengembalikan nilai 0 setelah selesai dieksekusi.


{….}
Kurung kurawal dinamakan block statement yang gunanya untuk mengurung beberapa statement menjadi 1 statement.


 float L, p, l;

float digunakan untuk menampung angka pecahan. Luas dengan tipe float digunakan untuk menampilkan hasil dari perhitungan luas persegi panjang dengan format bilangan pecahan.


cout << "=================================\n";
cout << "Program Menghitung Luas Persegi Panjang\n";
cout << "=================================\n";
cout << "Masukkan nilai panjang =";
cin >> p;
cout << "Masukkan nilai lebar =";
cin >> l;
L = p*l
cout << "Luas Persegi Panjang =" << (L) << endl;
Fungsi cout adalah fungsi standar pada C++ untuk menampilkan output ke layar. Simbol << digunakan untuk menuliskan teks yang akan ditampilkan ke layar. Teks harus diapit dengan tanda petik dan untuk membuat baris baru bisa menggunakan endl atau simbol \n, disini saya menggunakan \n.
Fungsi cin (c input) adalah fungsi untuk mengambil input dari keyboard. Fungsi cin membutuhkan variabel untuk menyimpan data yang diinputkan. Variabel berfungsi untuk meyimpan data saat program berjalan.
  L = p*l
Merupakan rumus luas persegi panjang.


 return 0;
return 0; digunakan untuk memberitahu bahwa kode telah selesai di esekusi dengan exit code 0.
