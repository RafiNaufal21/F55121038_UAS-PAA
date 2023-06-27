# UAS-PAA
Nama : Rafi Naufal Yassar Ramadhan

Nim  : F55121038

Kelas A

No. 1
Untuk menganalisis algoritma bubble sort dan insertion sort yang diberikan, kita akan melakukan evaluasi pada tiga kasus: Worst case, Best case, dan Average case. Berikut adalah analisis untuk masing-masing kasus:

Worst Case:

1. Worst case pada kedua algoritma terjadi ketika elemen-elemen dalam array tidak terurut dan harus diurutkan secara ascending.
2. Pada kedua algoritma, waktu eksekusi maksimum terjadi saat elemen-elemen array harus dipindahkan atau ditukar secara berulang untuk mencapai urutan yang benar.
3. Pada bubble sort, ini terjadi ketika elemen terbesar berada di posisi awal array dan harus dipindahkan ke posisi akhir dengan melakukan pertukaran pada setiap iterasi.
4. Pada insertion sort, worst case terjadi ketika setiap elemen harus disisipkan di posisi awal array dan harus memindahkan elemen-elemen lain untuk memberikan ruang bagi elemen baru.
5. Dalam kasus worst case, baik bubble sort maupun insertion sort memiliki kompleksitas waktu O(n^2).
Kesimpulan: Kedua algoritma memerlukan waktu eksekusi yang lama untuk menyelesaikan sorting pada worst case.

Best Case:

1. Best case pada kedua algoritma terjadi ketika elemen-elemen dalam array sudah terurut secara ascending.
2. Pada bubble sort, dalam best case, tidak ada pertukaran yang perlu dilakukan karena array sudah terurut dengan benar.
3. Pada insertion sort, dalam best case, pergeseran elemen hanya perlu dilakukan sedikit atau tidak sama sekali karena setiap elemen sudah pada posisi yang tepat.
4. Dalam kasus best case, bubble sort memiliki kompleksitas waktu O(n), sementara insertion sort memiliki kompleksitas waktu O(n).
Kesimpulan: Insertion sort lebih efisien dalam best case karena membutuhkan waktu eksekusi yang lebih singkat dibandingkan bubble sort.

Average Case:

1. Average case pada kedua algoritma terjadi ketika elemen-elemen dalam array tersebar secara acak dan tidak terurut.
2. Pada kedua algoritma, waktu eksekusi bergantung pada banyaknya perbandingan dan pertukaran elemen yang diperlukan untuk mengurutkan array.
3. Dalam kasus average case, bubble sort memiliki kompleksitas waktu O(n^2), sementara insertion sort memiliki kompleksitas waktu O(n^2).
4. Meskipun kedua algoritma memiliki kompleksitas waktu yang sama dalam average case, insertion sort cenderung sedikit lebih cepat karena membutuhkan lebih sedikit perbandingan dan pertukaran elemen.
Kesimpulan: Insertion sort sedikit lebih efisien daripada bubble sort dalam average case, tetapi keduanya masih memiliki kompleksitas waktu yang tinggi.

Kesimpulan :

 Bubble sort memiliki kinerja yang buruk dalam segala kasus (worst case, best case, dan average case) karena selalu memiliki kompleksitas waktu O(n^2).
Insertion sort lebih efisien dalam best case dan average case dibandingkan bubble sort, tetapi tetap memiliki kompleksitas waktu O(n^2).
Dalam situasi nyata, ketika berurusan dengan jumlah data yang besar, algoritma sorting dengan kompleksitas waktu O(n^2) seperti bubble sort dan insertion sort mungkin tidak efisien.
Untuk jumlah data yang besar, algoritma sorting dengan kompleksitas waktu lebih baik seperti quicksort, mergesort, atau heapsort umumnya lebih disarankan.

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
   
Average Case:
1. Kita dapat menggunakan grafik dengan sejumlah simpul dan tepi yang sedang dalam kasus rata-rata.
2. Misalnya, kita dapat menggunakan grafik yang sama yang digunakan dalam kode program, yang memiliki 7 simpul dan 13 tepi.
3. Dalam situasi ini, kompleksitas waktu TSP dan Djikstra akan bergantung pada kompleksitas algoritma yang digunakan oleh masing-masing. Sementara Djikstra menggunakan pendekatan greedy, TSP menggunakan pendekatan aproksimasi.

Kesimpulan :

   TSP memiliki kompleksitas waktu yang lebih tinggi daripada Dijkstra, terutama pada kasus terburuk dan average case.
Dijkstra lebih efisien dalam mencari jalur terpendek antara dua simpul dalam graf terhubung dengan bobot non-negatif.
Untuk masalah TSP dengan jumlah simpul yang besar, pendekatan heuristik mungkin lebih praktis daripada algoritma TSP eksakta.
Dalam memilih algoritma, perlu mempertimbangkan karakteristik masalah, ukuran graf, dan kebutuhan waktu eksekusi.

