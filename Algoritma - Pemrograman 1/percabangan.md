# Percabangan

## Apa itu Percabangan ?

Percabangan adalah suatu keadaan dimana pernyataan dapat dieksekusi apabila suatu  kondisi memenuhi syarat untuk mengerjakan pernyataan tersebut.

Didalam pemrograman kita harus dapat menentukan aksi apa yang harus dikerjakan oleh pemroses (processor) ketika sebuah kondisi terpenuhi, dengan menggunakan operasi logika.

> Contoh dalam Flowchart
>
> ![Percabangan](https://github.com/himasif/Library/raw/master/Semester%20Gasal/Algoritma%20-%20Pemrograman%201/img/percabangan.png)

## Jenis Percabangan

#### A. Percabangan Bertingkat
Percabangan bertingkat merupakan percabangan yang memiliki lebih dari dua kondisi, dengan kata lain terdapat sebuah percabangan lagi di sisi else (jika kondisi sebelumnya salah).

__Contoh :__

> Flowchart :
>
> ![Percabangan Bertingkat](https://github.com/himasif/Library/raw/master/Semester%20Gasal/Algoritma%20-%20Pemrograman%201/img/percabangan_bertingkat.png)

__ JAVA __

``` Java
if (a > 100){
  System.out.println("Nilai A Lebih dari 100");
} else if(a > 50){
  System.out.println("Nilai A Lebih dari 50 dan kurang dari 100");
} else{
  System.out.println("Nilai A Kurang dari 50");
}
```

#### B. Percabangan Bersarang
Percabangan bersarang merupakan percabangan yang lebih dari 2 kondisi, terdapat if didalam if.

__Contoh :__

> Dalam Flowchart
>
> ![Percabangan Bersarang](https://github.com/himasif/Library/raw/master/Semester%20Gasal/Algoritma%20-%20Pemrograman%201/img/percabangan_bersarang.png)

__JAVA__

``` Java
if (a > 100){
  if (a < 200){
    System.out.println("Nilai A lebih dari 100 dan kurang dari 200");
  }
} else{
  System.out.println("Nilai A kurang dari 100");
}
```
