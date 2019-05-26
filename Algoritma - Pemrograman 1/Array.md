# Array
### Konsep
Array merupakan variabel yang digunakan untuk menyimpan sejumlah data dengan tipe yang sama. Array dapat dianalogikan kotak pensil dan isinya. Array berguna untuk mempersingkat	jumlah variabel.  

###Deklarasi variabel array
array dideklarasikan hampir sama dengan pendeklarasian variabel biasa, namun dengan menambahkan kurung siku "[ ]"

>__Deklarasi variabel array__
>.
>typeData[] namaArray;
>.
>atau
>.
>typeData namaArray[];

Untuk menggunakan array, diperlukan keyword "new" dan jumlah elemen yang disediakan

>__Penggunaan array__
>.
>namaArray = new typeData[jumlahElement]
>.
>atau bisa digabung dengan pendeklarasian
>.
>typeData[] namaArray = new typeData[jumlahElement]

Pernomoran index array dimulai dari 0. Misal, jika suatu array berisi 5 element, maka penomorannya adalah 0, 1, 2, 3, 4.

###Mengisi array
Mengisi array bisa dilakukan dengan berbagai cara. Array bisa diisi dengan mengisi tiap element satu per satu, mengisi langsung seluruh element array sekaligus, atau menggunakan perulangan (looping).

>__Cara mengisi array__
>.
>--mengisi per element--
>.
>namaArray[0] = "isi 1";
>namaArray[1] = "isi 2";
>dst.
>.
>.
>--mengisi langsung seluruh element sekaligus--
>.
>typeData[] namaArray = {"isi 1","isi 2"};
>.
>.
>--dengan bantuan looping dan scanner--
>.
>Scanner namaScanner = new Scanner(System.in);
>for(i=0; i<jumlahElement; i++)
>{
>		System.out.print("isi ke - " + i + " ");
> 	namaArray[i]=namaScanner.next();
>}

   

