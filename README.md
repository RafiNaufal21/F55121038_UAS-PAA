# UAS-PAA
Nama : Rafi Naufal Yassar Ramadhan

Nim  : F55121038

Kelas A

No. 1


No. 2 

TSP (Problem Salesman Travelling) dan Djikstra adalah dua algoritma yang digunakan dalam hal ini.

worst case:
1. Dalam situasi terburuk, kita dapat mempertimbangkan graf yang sangat kompleks dengan banyak simpul(vertex) dan tepi(edge) yang saling terhubung, yang akan memaksa algoritma untuk memeriksa sebagian besar jalur yang mungkin.
2.  Misalnya, kita dapat mempertimbangkan graf dengan sepuluh simpul yang dihubungkan secara acak dengan bobot yang berbeda di setiap tepi. Algoritma akan mencari jalur terpendek dengan memeriksa semua permutasi simpul yang mungkin.
3. Dalam hal ini, baik TSP maupun Dijkstra akan memiliki kompleksitas waktu yang tinggi; karena kompleksitasnya yang eksponensial, TSP akan membutuhkan lebih banyak waktu.
   
Best Case:
1. Dalam skenario terbaik, kita dapat mempertimbangkan graf yang sangat sederhana yang memiliki sedikit simpul dan tepi yang saling terhubung.
2. Misalnya, kita dapat mempertimbangkan graf dengan tiga simpul yang membentuk segitiga dan memberikan bobot yang sama pada setiap tepinya
3. Karena jumlah simpul dan tepi yang sedikit, TSP dan Dijkstra akan memberikan hasil dengan cepat.
   
Case Average:
1. Kita dapat menggunakan grafik dengan sejumlah simpul dan tepi yang sedang dalam kasus rata-rata.
2. Misalnya, kita dapat menggunakan grafik yang sama yang digunakan dalam kode program, yang memiliki 7 simpul dan 13 tepi.
3. Dalam situasi ini, kompleksitas waktu TSP dan Djikstra akan bergantung pada kompleksitas algoritma yang digunakan oleh masing-masing. Sementara Djikstra menggunakan pendekatan greedy, TSP menggunakan pendekatan aproksimasi. 
