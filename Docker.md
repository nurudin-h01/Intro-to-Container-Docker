<b >1. Jelaskan apa yang dimaksud dengan container pada docker ! </b>

Container pada docker adalah sebagai wadah yang bertujuan untuk mengemas juga menjalankan aplikasi. Wadah ini mencakup kode, runtime, system tools, dan pengaturan. Container juga hanya bisa mengakses resource yang telah ditentukan dalam Docker image

<b> 2. Jelaskan apa perbedaan antara konsep container dengan virtual machine ! </b>

Container dapat berjalan langsung diatas sistem operasi dan container sendiri tidak diizinkan untuk mengakses kernel. sedangkan virtual machine menggunakan kernel tersendiri untuk menjalankan aplikasi didalamnya

<b> 3. Apa yang dimaksud dengan docker file ? </b>

Dokumen teks yang berisi semua perintah yang dapat dipanggil pengguna pada baris perintah untuk membuat image

<b> 4. Apa yang dimaksud dengan docker registery ? </b>

docker registery adalah tempat untuk hosting atau menyimpan gambar yang kita miliki sehingga dapat diakses banyak orang

<b> 5. Jelaskan bagaimana cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung ! </b>

Dengan cara membuat Docker Compose, Docker Compose adalah alat untuk mendefinisikan dan menjalankan satu atau beberapa container yang saling terkait dengan sebuah command. Code yang telah dibuat di dalam docker compose selanjutnya disimpan dengan ektensi yaml
