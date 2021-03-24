# Depth First Search

Depth First Search pelacakan atau pencarian yang bermula dari akar ke cabang cabangnya. Jadi disini pencarian node dimulai dari node akar atau node awal menuju cabang node sampai ke tujuan akhir.

Pada kode DFS tersebut, dijelaskan bahwa kita akan membuat grafik yang akan kita gunakan pada Depth First Search. Dilanjutkan dengan kita membuat satu set untuk menyimpan nilai node yang dikunjungi untuk melacak node yang dikunjungi dari grafik.

Setelah proses tersebut maka kita dapat mendeklarasikan fungsi dengan parameter sebagai node yang dikunjungi, grafik itu sendiri, dan node masing-masing. Dan di dalam fungsinya, kita akan memeriksa apakah ada node dari grafik dengan menggunakan kondisi "if". Jika tidak, maka dapat mencetak node dan menambahkannya ke kumpulan node yang dikunjungi.
Selanjutnya pada node neighbour dari grafik serta sekali lagi memanggil fungsi DFS untuk menggunakan parameter neighbour.
Terakhir, kita akan menjalankan kode driver untuk mencetak hasil akhir DFS dengan memanggil DFS pertama kali dengan simpul awal grafik.

Hasil :
3
2
4
8
7

# Breadth-First Search

Breadth-First Search Pelacakan atau pencarian node dengan perlevel atau perbaris yang dapat diartikan mendatar.
Pada kode program tersebut seperti biasa dimulai dari pembuatan grafik lalau kita membuat dua daftar, satu untuk menyimpan nodel yang dikunjungi dari grafik dan untuk menyimpan node dalam antrian.

Kemudian kita deklarasikan fungsi dengan parameter sebagai node yang dikunjungi, grafik itu sendiri, dan node masing-masing pada sebuah fungsi, dengan terus menambahkan daftar atau list yang dikunjungi dan antrian.

Selanjutnya dijalankan fungsi while loop untuk antrian untuk mengunjungi node dan kemudian akan menghapus node yang sama dan mencetaknya saat dikunjungi.
Terakhir, dijalankan fungsi loop for untuk memeriksa node yang tidak dikunjungi dan kemudian menambahkan node yang sama dari daftar yang dikunjungi dan antrian. Dan kode driver, sebagai pencetak hasil.

Hasil :
5 3 7 2 4 8
