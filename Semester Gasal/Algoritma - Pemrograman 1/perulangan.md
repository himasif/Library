# Perulangan
### Konsep
Perulangan merupakan perintah untuk mengulang suatu statement atau blok berulang kali. Kondisi ditetapkan sebelum melakukan perulangan agar tidak terjadi infinite loop. Statement yang sering digunakan adalah for, while do, dan do while  

###Statement for 
Paling mudah diterapkan sebagai penghitung. Statement for lebih efektif diterapkan untuk perulangan dengan jumlah perulangan sangat kecil.	 

> __Struktur Statement For__  
> .
> for(Inisialisasi nilai; evaluasi nilai sekarang; perubahan nilai)
>		{
>			Statement;
>		}  

Statement for juga memiliki bentuk lain, yaitu statement for bersarang. Contoh penggunaan for bersarang adalah membuat matriks bilangan dan array multidimensi.
> __Struktur Statement For Bersarang__  
> .
> for(Inisialisasi nilai2; evaluasi nilai1 sekarang; perubahan nilai1)
>		{
>     for(inisialisasi nilai2; evaluasi nilai2 sekarang; perubahan nilai2)
>			{
>				Statement;
>			}
>		}  


###Statement while-do
Merupakan bentuk perulangan yang hanya membutuhkan evaluasi kondisi. Sementara kondisi terpenuhi, maka perulangan akan terus dilakukan

>__Struktur Statement While-Do__
>.
>while(evaluasi kondisi)
>		Statement;

###Statement do-while
Merupakan bentuk perulangan kebalikan dari while-do. Jika kondisi belum terpenuhi, maka perulangan terus dilakukan
>__Struktur Statement Do-While__
>.
>do 
>   {
>     Statement
>   }
>while(Evaluasi Kondisi)

