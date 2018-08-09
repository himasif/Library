# Software & Bahasa Pemrograman

### A. Software
#### Definisi
Software adalah Program Komputer yang berfungsi sebagai sarana interaksi antara pengguna dan perangkat keras. Selain itu software juga dikatakan sebagai 'penterjemah' perintah-perintah dr pengguna untuk diteruskan ke atau diproses oleh perangkat keras.

![Software](http://himasif.ilkom.unej.ac.id/library/Software_1.png)

Software secara umum berisi instruksi untuk mengerjakan prosedur tertentu, baik memproses data, melakukan perhitungan, berinteraksi dengan software lain (OS maupun aplikasi lainnya) hingga mengontrol perangkat keras (disebut device driver).

__Contoh :__
```  C
#include <stdio.h>
int main(){
  int a, b;
  a = 4;
  b = a + 6;
  if (a == 5)
      printf (“Nilai a samadengan 5”);
  if (b > 9) 
      printf (“Nilai b memang lebih besar dari 9”);
}
```
  
  
#### Kategori Software
Secara umum Software dibagi menjadi 3 kategori, yaitu :
* Sistem Operasi
* Program Aplikasi
* Bahasa Pemrograman
  
###### A. Sistem Operasi
Sistem operasi adalah subkelas software lapisan pertama (pertama kali diletakkan di memori komputer saat dinyalakan) dan bertugas mengontrol & mengelola hardware serta menyediakan operasi dasar sistem (akses ke disk, manajemen memori, skeduling task, dan antar-muka user).
Sistem operasi juga bertindak sebagai host bagi semua aplikasi yg dijalankan pada komputer menangani detail operasi terhadap hardware.

> __Contoh:__  
Microsoft: MSDOS, MS Windows 2000, MS Windows XP, Vista  
Linux: Fedora, CentOS, Ubuntu, Slackware, Symbian  
Novell: Netware  
Android : KitKat, Marsmallow, Nouggat, Oreo  
Apple: iOS  
  
  
###### B. Program Aplikasi
Program aplikasi adalah subkelas software yg didesain bagi end user untuk memanfaatkan kemampuan komputer secara langsung. Program aplikasi digunakan untuk melakukan tugas yang spesifik. Program aplikasi juga membutuhkan Sistem Operasi untuk dijalankan. 

> __Contoh:__  
__Pengolah Kata:__ Untuk menghasilkan (termasuk membuat, meng-edit, menata tampilan, serta mencetak) berbagai materi/dokumen teks.  
![Microsoft Word](https://cdn1.tekrevue.com/wp-content/uploads/2015/02/word-search-with-bing.jpg)  
>__Spreadsheet:__ mensimulasikan kertas lembar kerja, yang tersusun dalam format baris dan kolom untuk membentuk cel-cel yg dpt diisi dng data dan formula  
![Microsoft Excel](https://d2myx53yhj7u4b.cloudfront.net/sites/default/files/styles/full_width_desktop/public/IC-how-to-make-spreadsheet-11%20copy.jpg?itok=aDdzCSmp)  
> __Pengolah Gambar:__ Untuk menghasilkan (termasuk membuat, meng-edit, menata tampilan, serta kemungkinan pencetakan) berbagai materi/dokumen gambar.  
![Corel Draw](https://images-na.ssl-images-amazon.com/images/I/61PdhuOvizL._SL1024_.jpg)  

###### C. Bahasa Pemrograman
Bahasa Pemrograman adalah subkelas dari sotfware yang digunakan untuk menulis (membuat) software. Bahasa Pemrograman berfungsi untuk menterjemahkan seluruh kode program yang dibuat ke bahasa mesin. Bahasa Pemrograman dibagi menjadi 2, yaitu Bahasa Tingkat Tinggi dan Bahasa Tingkat Rendah.

> __Untuk lebih jelasnya silahkan lihat video ini__  
@[youtube](bUWCD45qniA)
  
  
###### Bahasa Tingkat Rendah
* Sekumpulan perintah/instruksi yang memiliki struktur & perintah bahasa mesin/seperti bahasa mesin
* Bukan bahasa mesin, merupakan pengkodean instruksi bahasa mesin untuk mempermudah penyusunan program
* Didesign sesuai dengan CPU yang digunakan

__Contoh :__  
__Bahasa Mesin__
```
000000 00001 00010 00110 00000 100000
```

__Bahasa Assembly__
```Assembly
mov     ax,4C00h
int     21h 
```
  
   
###### Bahasa Tingkat Tinggi
* Sekumpulan perintah/instruksi untuk menyusun program yang tidak tergantung pada CPU yang digunakan
* Membutuhkan “penterjemah” (Compiler/Interpreter) agar dapat diproses oleh mesin
* “English like” language
 
__Contoh :__  

__Bahasa Java__  
```Java
public class Main{
    public static void main(String[] args){
        int a = 16;
        int b = 33;
        int c = a * b;
        if(c > 500){
            System.out.println("Gede");
        }
        else{
            System.out.println("Kecil");
        }
    }
}
```

__Bahasa Ruby__
```Ruby
n = 322
n.times{ |i| puts "Hello Maba" + "a" * i }
```

#### Tingkatan Bahasa Pemrograman

![Ladder](https://2.bp.blogspot.com/-g32NL_Q7iLE/WPZNcurHJhI/AAAAAAAAAGw/KfgIQMhN5_Ms7ixgGFEtray-1jLs1R17QCLcB/s1600/chapter-3-instruction-set-and-assembly-language-programming-6-638.jpg)
