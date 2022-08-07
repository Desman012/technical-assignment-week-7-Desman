Kamu adalah seorang programmer yang bekerja pada suatu start-up terkini, kemudian kamu diminta untuk menyusun folder dan files sebagai bentuk dokumentasi dari berkas-berkas yang kamu miliki. Kamu diminta untuk

1. membuat sebuah folder kosong dengan nama-mu sendiri
    ```bash
    mkdir desman
    ```
    ![Screenshot 2022-07-26 072732](https://user-images.githubusercontent.com/107124396/180897135-e5143b2d-43b3-45d1-8a04-5628422e39f8.png)
    <br><br>
2. didalam *folder* tersebut buatlah
    - *folder* `sekolah`
    - *folder* `kerja`
    <br>
```bash
    mkdir sekolah
    mkdir kerja
```

3. masuk ke dalam folder `sekolah`
    - buat *file* dengan nama `ijazah.txt`, yang mana file tersebut akan memiliki teks seperti:

        ```jsx
        Perkenalkan namaku $NAMA

        Aku berasal dari $DAERAH

        Salam Kenal :D
        ```

        - $NAMA ⇒ diganti dengan namamu sendiri
        - $DAERAH ⇒ diganti dengan daerah asalmu sendiri
    - tampilkan isi dari *file* tersebut menggunakan `CLI command`
    - kemudian buat 1 file lagi dengan nama `portfolio.txt`, yang mana file tersebut akan memiliki teks seperti:

        ```jsx
        Saya pernah bekerja pada beberapa perusahaan salah satu 
        diantaranya ialah

        - $PERUSAHAAN
        - $PERUSAHAAN
        - $PERUSAHAAN
        ```

        - $PERUSAHAAN ⇒ diganti dengan nama perusahaan yang kamu sukai
```bash
    cd sekolah
    nano ijazah.txt
    cat ijazah.txt
    nano portfolio.txt
```<br>
    ![Screenshot 2022-08-07 233020](https://user-images.githubusercontent.com/107124396/183301162-905e2b6b-5ce1-48bd-a9ac-b9fd64935800.png)


4. keluar dari *folder* sekolah
```bash
    cd ..
```
5. masuk kedalam *folder* `kerja`
    - buat *file* dengan nama `cv.txt`, yang mana hal tersebut akan memiliki teks seperti:

        ```jsx
        Salam,

        Perkenalkan namaku $NAMA, saya memiliki kegemaran
        - $HOBBY
        - $HOBBY
        - $HOBBY
        ```

        - $NAMA ⇒ diganti dengan namamu sendiri
        - $HOBBY ⇒ diganti dengan hobi-mu sendiri
    - tampilkan isi dari *file* tersebut menggunakan `CLI command`
```bash
    cd kerja
    nano cv.txt
    cat cv.txt
```
6. Pada tahap ini kamu lupa jika sebenarnya *file* `portfolio.txt` serahusnya tidak berada pada *folder* `sekolah`, jadi kamu harus **memindahkannya** ke dalam folder `kerja`
```bash
    cd ../sekolah
    mv portfolio.txt ../kerja/
```
