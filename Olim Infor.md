
## BAB 1
## A - Program pertamaku
diseesaikan oleh kian
``` cpp
#include <iostream>

int main() {
    std::cout << "Halo, dunia!"<< std::endl;
}
```

## B - Mencetak dengan std::cout
diselesaikan oleh kian
```cpp
#include <iostream>

int main() {
    std::cout << "Halo, dunia!" << std::endl;
    std::cout << "Aku semangat belajar C++!" << std::endl;
}
```

## C - Mencetak Bilangan
diselesaikan oleh kian
```cpp
#include <iostream>

int main() {
    std::cout << "Halo, dunia!" << std::endl;
    std::cout << "Aku semangat belajar C++!" << std::endl;
}
```

## D - Menjumlahkan Bilangan
diselesaikan oleh kian
``` cpp
#include <iostream>

int main() {
    std::cout << "Pak Dengklek memiliki " << 738 + 519 << " ekor bebek." << std::endl;
}

```

## F - Mengukur Kandang
diselesaikan oleh kian
``` cpp
#include <iostream>

int main() {
    // cetak luas kandang
    std::cout << 364*79 << std::endl;

    // cetak keliling kandang
    std::cout << 2*(364+79) << std::endl;
}
```


## BAB 2
## A -
diselesaikan oleh kian

## B. Perkenalan Variabel
diselesaikan oleh kian

```cpp
#include <iostream>
using namespace std;

int main() {
    int panjang = 364;
    int lebar = 79;

    // cetak luas kandang
    cout << panjang*lebar << endl;

    // cetak keliling kandang
    cout << 2*(panjang + lebar) << endl;
}
```

## C. Memperbarui Nilai Variabel
diselesaikan oleh kian
```cpp
#include <iostream>
using namespace std;

int main() {
    // kata sandi bulan pertama
    int sandi = 174;
    cout << sandi << endl;

    // kata sandi bulan kedua
    sandi = 23*sandi;
    cout << sandi << endl;

    // kata sandi bulan ketiga
    sandi = 23*sandi;
    cout << sandi << endl;
}

```

## D. Kuis Perubahan Nilai Variabel
diselesaikan oleh kian

## E. Perkenalan Tipe Data String
diselesaikan oleh kian
```cpp
#include <iostream> // untuk menggunakan cout dan endl
#include <string>   // untuk menggunakan string
using namespace std;

int main() {
    int tanggal = 15;
    int tahun = 2023;

    // jangan lupa bahwa string perlu diapit dengan kutip dua
    string bulan = "Februari"; 

    // cetak kata sandi
    cout << tahun +10 << "-" << bulan << "-" << tanggal +7<< endl;
}

```

## F. Aturan Variabel
diselesaikan oleh kian

## G. Jual-Beli Bebek
diselesaikan oleh kian
```cpp
#include <iostream>
using namespace std;

int main() {
	int jantan, betina;
 
    // banyaknya bebek saat ini
	jantan = 63;
	betina = 192;
 
    // setelah bulan pertama
	betina = betina + jantan;
	jantan = jantan - jantan/3;
 
    // setelah bulan kedua
	jantan = betina + jantan;
	betina = betina - 10;
 
    // cetak total bebek
	cout << jantan + betina << endl;
}
```

###  H. Rangkuman: Variabel dan Tipe Data
diselesaikan oleh kian

## BAB 3
## A. Variasi Operasi Assignment
diselesaikan oleh kian

### B. Membeli Kandang
diselesaikan oleh kian
```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;

    // bulan pertama
    luas_kandang += 7;
    cout << luas_kandang << endl;

    // bulan kedua
    luas_kandang += 7;
    cout << luas_kandang << endl;

    // bulan ketiga
    luas_kandang += 7;
    cout << luas_kandang << endl;
}

```

### C. Perkenalan While
diselesaikan oleh kian
```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;

    while (luas_kandang < 33) {
        luas_kandang += 7;
        cout << luas_kandang << endl;


    }
}
```

### D. Pendalaman While
diselesaikan oleh kian

### E. Membeli Kandang II
diselesaikan oleh kian
```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;
    int nomor_baris = 1;

    while (nomor_baris <= 3) {
        luas_kandang += 7;
        cout << nomor_baris << ": " << luas_kandang << endl;

        nomor_baris += 1;
    }
}

```

### F. Membeli Kandang III
diselesaikan oleh kian
```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;
    
    // Menyatakan sudah berapa bulan (berapa kali) Pak Dengklek
    // membeli kandang baru.
    int total_bulan = 0;

    // Menyatakan total luas kandang yang dimiliki Pak Dengklek.
    // Pada mulanya, totalnya adalah luas kandang lama Pak Dengklek.
    int total_luas_kandang = luas_kandang;

    while (total_bulan < 10) {
        luas_kandang += 7;
        total_luas_kandang += luas_kandang;

        total_bulan += 1;
    }

```

### G. Membeli Kandang IV
diselesaikan oleh kian
```cpp
#include <iostream>
using namespace std;

int main() {
    // Menyatakan total banyaknya kandang yang dimiliki Pak Dengklek.
    // Pada mulanya, Pak Dengklek memiliki 1 kandang seluas 12 meter persegi.
    int total_kandang = 1;
    int luas_kandang = 12;

    int total_luas_kandang = luas_kandang;

    while (total_luas_kandang < 800) {
        luas_kandang += 7;
        total_luas_kandang += luas_kandang;

        total_kandang += 1;
    }

    cout << total_kandang << endl;
}
```

### H. Jual-Beli Bebek II
diselesaikan oleh kian
```cpp
#include <iostream>
using namespace std;

int main() {
    int jantan = 0, betina = 0;
    int tanggal = 1;

    while (betina <= 10*jantan) {
        jantan += 1;
        betina += tanggal;
        tanggal += 1;
    }

    cout << tanggal << endl;
}

```

### I. Rangkuman: Perulangan
diselesaikan oleh kian

## BAB 4

### A. Perkenalan If
diselesaikan oleh kian

### B. Menggiring Bebek
diselesaikan oleh kian

```cpp
#include <iostream>
using namespace std;

int main() {
    int jantan = 67;
    int betina = 98;

    if (jantan % 2 == 0) {
        cout << "banyaknya bebek jantan adalah bilangan genap" << endl;
    }

    if (betina% 2 == 0) {
        cout << "banyaknya bebek betina adalah bilangan genap" << endl;
    }
}

```


### C. Perkenalan Else
diselesaikan oleh kian

```cpp
#include <iostream>
using namespace std;

int main() {
    int total_bebek = 67 + 98;

    if (total_bebek % 2 == 0) {
        cout << "total banyaknya bebek adalah bilangan genap";}
    else
        cout << "total banyaknya bebek adalah bilangan ganjil";
}

```

### D. Perkenalan Else If
diselesaikan oleh kian

```cpp
#include <iostream>
using namespace std;

int main() {
    int total_bebek = 67 + 98;
    
    if (total_bebek % 13 == 0) {
        cout << 13 << endl;
    }
    else if (total_bebek % 11 == 0) {
        cout << 11 << endl;
    }
    else if (total_bebek % 5 == 0) {
        cout << 5 << endl;
    }
    else if (total_bebek % 3 == 0) {
        cout << 3 << endl;
    } else {
        cout << 1 << endl;
    }
}

```

### E. Kuis If
diselesaikan oleh kian

### F. Pendalaman Ekspresi Boolean
diselesaikan oleh kian

### G. Mengukur Kandang II
diselesaikan oleh kian

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    int A = 364 * 79;
    int B = 243 * 99;
    int C = 189 * 155;
    
    string terbesar, terkecil;

    if (A > B && A > C) {
        terbesar = "A";


        if (B < C) {
            terkecil = "B";
        } else {
            terkecil = "C";
        }
    } else if (B>A && B>C) {
        terbesar = "B";

        if (A<C) {
            terkecil = "A";
        } else {
            terkecil = "C";
        }
    } else {
        terbesar = "C";

        if (A<B){
        terkecil = "A";
        } else{
            terkecil = "B";}
        }
    cout << terbesar << endl;
    cout << terkecil << endl;
}
```

### H. Rangkuman: Percabangan
diselesaikan oleh kian


## BAB 5


### A. Perkenalan For
diselesaikan oleh kian

```cpp
#include <iostream>
using namespace std;

int main() {
    for (int sisi = 121; sisi <= 125; sisi += 1) {
        cout << sisi*sisi << endl;
    }
}

```

### B. Perkenalan Tipe Data Boolean
diselesaikan oleh kian

```cpp
#include <iostream>
using namespace std;

int main() {
    bool ada_yang_dijual = false;

    for (int sisi = 121; sisi <= 125; sisi++) {
        bool kelipatan_2 = sisi % 2 == 0;
        bool kelipatan_3 = sisi % 3 == 0;

        if (kelipatan_2 && !kelipatan_3) {
            ada_yang_dijual = true;
        }
    }

    if (ada_yang_dijual) {
        cout << "ada" << endl;
    } else {
        cout << "tidak ada" << endl;
    }
}
```

### C. Perkenalan Continue dan Break
diselesaikan oleh kian (dibantu guru les saya, disuruh masukin kode yang dia buat soalnya)

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    for (int luas = 100000; luas <= 200000; luas++) {
        if (luas % 2 != 0) {
            continue;
        }
        bool kuadrat = false;
        int n = sqrt(luas);
        if (luas == n * n){
            kuadrat = true;
        }
        
        if (kuadrat){
            cout << luas << endl;
            break;
        }
    }
}
```

### D. Kuis Perulangan & Percabangan
diselesaikan oleh kian

### E. Mencari Pola I
diselesaikan oleh kian


```cpp
#include <iostream>
using namespace std;

int main() {
    int N = 10;

    for (int i = 1; i <= N; i++) {
        // cetak i buah "*"
        for (int j=1; j<=i; j++) {
            cout << "*";
        }

        // sisanya, cetak "."
        for (int j=i+1; j<=N; j++) {
            cout << ".";
        }

        cout << endl;
    }
}

```


### F. Mencari Pola II
diselesaikan oleh kian

```cpp
#include <iostream>
using namespace std;

int main() {
    int N = 10;

    for (int vertical = 1; vertical <= N; vertical++) {
        for (int horizonal = 1; horizonal <= N; horizonal++) {
            if (vertical ==1 || vertical==N || horizonal==1 || horizonal==N ) {
                // jika baris atau kolom saat ini adalah yang pertama atau terakhir, cetak bintang
                cout << "*";
            } else {
                // selain itu, cetak titik
                cout << ".";
            }
        }
        cout << endl;
    }
}

```
### G. Mencari Pola III
diselesaikan oleh kian


```cpp
#include <iostream>
using namespace std;

int main() {
    int N = 10;

    for (int i = 1; i <= N; i++) {
        for (int j= 1; j <= N; j++){
            if (i==j || i+j ==N+1)
               cout << "*";
            else
                cout << ".";
            }
     cout << endl;
    }
}
```

