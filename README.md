# Tugas 7: Elemen Dasar Flutter
Nama  : Arditio Reihansyah Putra Pradana
NPM   : 2106751972

## Counter_7
1. Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya.
- Stateless Widget  : Stateless Widget adalah widget statis yang statenya tidak dapat diubah setelah dibuat/diinisiasi. Contohnya adalah Icon, IconButton, dan Text. 
- Stateful Widget : Stateful Widget adalah widget dinamis yang statenya dapat diubah sebagai response dari events yang ditrigger oleh interaksi pengguna atau ketika menerima data. Contohnya adalah Checkbox, Radio, Slider, Inkwell, Form, dan TextField.

2. Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.
- Text =  Widget Text digunakan untuk menampilkan string
- Column = Widget Column digunakan untuk menampilkan children dalam array vertikal
- Center = Widget ini digunakan untuk men-center child di dalamnya
- Padding = Widget untuk memberikan padding
- Row = Widget untuk menampilkan childrennya dalam array horizontal
- Visibility = Widget untuk menampilkan/menyembunyikannya childnya
- FloatingActionButton = Untuk membuat Floating Action Button

3. Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.
setState() berguna untuk memberi pemberitahuan kepada flutter bahwa telah terjadi perubahan pada state tersebut. Fungsi ini kemudian akan menyebabkan flutter untuk melakukan build ulang sehingga perubahan yang terjadi dapat ditampilkan. Variabel yang terdampak dengan fungsi ini adalah seluruh variabel yang digunakan untuk menampilkan nilai dari variabel yang berubah, contohnya seperti widget-widget yang digunakan untuk menampilkan dari variabel yang berubah.

4. Jelaskan perbedaan antara const dengan final.
- Final : Final adalah keyword yang digunakan untuk variabel atau field yang valuenya tidak akan berubah. Sehingga ketika value di-assign ke sebuah variable maka value tersebut tidak bisa diganti/berubah
- Const : Mirip seperti final, tetapi perbedaannya value yang di-assign adalah nilai yang ada pada saat di compile

Const tidak dapat digunakan untuk variabel yang valuenya diperoleh saat runtime contohnya adalah DateTime.now() sehingga untuk kasus ini harus menggunakan final. Const digunakan ketika value yang disimpan sudah diketahui pada waktu compile seperti misalnya (const a = 1).

5. Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.
- Membuat flutter app counter_7 
- Membuat fungsi baru untuk decrement
- Membuat if-else untuk menampilkan teks ketika teks yang ditampilkan GENAP/GANJIL
- Membuat floating action button dengan memanfaatkan widget padding
- Mengamplikasikan floating action button pada widget visibility untuk melakukan hide/show dari tombol decrement

