
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