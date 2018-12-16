# Menghitung luas lingkaran

Alur algoritma:
1. Tentukan nama variabel yang akan menampung data jari-jari
2. Masukkan (inputkan) data jari-jari(r) dan harga phi pada variabel yang sudah ditentukan
3. Hitung luas ligkaran
4. Tampilkan (outputkan) luas lingkaran
5. Selesai


Flowchart program

![img](https://raw.githubusercontent.com/MUTIARAIZMI/Menghitung-luas-lingkaran/master/flowchart%20Luas%20Lingkaran.png)



Code Program lengkap


    #include <iostream>
    using namespace std;
    int main()
    {
    int r;
    float phi = 3.14,luas;

    cout<<"Masukkan jari-jari lingkaran =";
    cin>>r;

    luas = phi*r*r;
    cout<<"Luas lingkaran adalah ="<<luas;
    return 0;
    }



Hasil Program

![img](https://raw.githubusercontent.com/MUTIARAIZMI/Menghitung-luas-lingkaran/master/luas%20lingkaran.jpg)
