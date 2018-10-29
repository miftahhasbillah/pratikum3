# pratikum3

Pratikum 3

Latihan  1: mencari bilangan terbesar
	1. mendeklarasikan jumlah variabel
	2. mengisi nilai variabel
	3. menghitung bilangan terbesar dengan rumus 
		for (i;i<n;i++) {
        cout << "masukan bilangan ke-" << i+1 << ": ";
        cin >> a;

        if (a > max)
            max = a;

	4. mencetak hasil kelayar cout << "bilangan terbesar adalah: " << max << endl;

Dengan bahasa kode C++

#include <iostream>

using namespace std;

int main() {
    int i=0;
    int max=0;
    int n,a;

    cout << "masukan jumlah bilangan: ";
    cin >> n;

    for (i;i<n;i++) {
        cout << "masukan bilangan ke-" << i+1 << ": ";
        cin >> a;

        if (a > max)
            max = a;
    }

    cout << "bilangan terbesar adalah: " << max << endl;
}

**screenshoot**
![screenshoot](https://raw.githubusercontent.com/miftahhasbillah/pratikum3/master/SS%20LATIHAN%201.png)

**flowchart**
![flowchart](https://github.com/miftahhasbillah/pratikum3/blob/master/flowchart%20latihan1.jpg)

latihan 2 : mencari 3 bilangan terbesar
	1. mendekrasi kan 3 variabel A,B,C
	2. mengisi nilai variabel yang di inginkan
	3. menghitungkan angka terbesar dengan rumus if
	4. mencetak hasil kelayar dengan urutan angka terbesar

Dengan bahasa C++

#include<iostream>

using namespace std;

int main() {
    int A,B,C;

    cout << "masukkan bilangan A: "; cin >> A;
    cout << "masukkan bilangan B: "; cin >> B;
    cout << "masukkan bilangan C: "; cin >> C;

    if (A<B) {
        if (B<C)
            cout << "urutan bilangan: " << A << ", " << B << ", " << C << endl;
        else {
            if (A<C)
                cout << "urutan bilangan: " << A << ", " << C << ", " << B << endl;
            else
                cout << "urutan bilangan: " << C << ", " << A << ", " << B << endl;

        }
    } else {
        if (A<C)
            cout << "urutan bilangan: " << B << ", " << A << ", " << C << endl;
        else {
            if (B<C)
                cout << " urutan bilangan: " << B << ", " << C << ", " << A << endl;
            else
                cout << " urutan bilangan: " << C << ", " << B << ", " << A << endl;

        }
    }
}

**screenshoot**
![screenshoot](https://raw.githubusercontent.com/miftahhasbillah/pratikum3/master/SS%20LATIHAN%202.png)

**flowchart**
![flowchart](https://raw.githubusercontent.com/miftahhasbillah/pratikum3/master/FLOWCHART%20LATIHAN2.png)

Latihan 3 : susun algoritma untuk menginput 3 buah bilangan bulat, (dianggap ketiga buah bilangan tersebut nilainya tidak sama satu dengan yang lain). kemudian cetaklah bilangan dengan nilai tengah (bukan terbesar juga bukan yang terkecil)
 
	1. mendeklarasikan 3 variabel A,B,C
	2. mengisi nilai variabel yang di inginkan
	3. menghitung dengan rumus if
	4. mencetak hasil kelayar dengan nilai tengah
Dengan bahasa C++

 #include<iostream>

using namespace std;

int main() {
  cout<<"Program Menentukan Bilangan Tengah Dari 3 Bilangan Yang Berbeda "<<endl;
  int a,b,c;
  cout<<"1.Masukkan bilangan pertama = ";
  cin>>a;
  cout<<"2.Masukkan bilangan kedua   = ";
  cin>>b;
  cout<<"3.Masukkan bilangan ketiga  = ";
  cin>>c;

  if(b<c && a>c)
  cout<<"bilangan tengah adalah bilangan C"     ;
  else if(b>c && a<c)
  cout<<"bilangan tengah adalah bilangan C"     ;
  else if(c<b && c>a)
  cout<<"bilangan tengah adalah bilangan C"     ;
  else if(c>b && c<a)
  cout<<"bilangan tengah adalah bilangan C"     ;
  else if(b<a && a>c)
  cout<<"bilangan tengah adalah bilangan B"     ;
  else if(b>a && a<c)
  cout<<"bilangan tengah adalah bilangan B"     ;
  else if(a<b && c>a)
  cout<<"bilangan tengah adalah bilangan B"     ;
  else if(a>b && c<a)
  cout<<"bilangan tengah adalah bilangan B"     ;
  else if(b>a && c<a)
  cout<<"bilangan tengah adalah bilangan A"     ;
  else if(b<a && c>a)
  cout<<"bilangan tengah adalah bilangan A"     ;
  else if(a>b && a<c)
  cout<<"bilangan tengah adalah bilangan A"     ;
  else if(a<b && a>c)
  cout<<"bilangan tengah adalah bilangan A"     ;

 }

**screenshoot**
![screenshoot](https://raw.githubusercontent.com/miftahhasbillah/pratikum3/master/SS%20latihan3.png)
