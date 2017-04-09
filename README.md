# tugasXSD_Webservice1154019
Simon Sorba Manangi/1154019

Dalam praktek xsd ini ada 2 file yang terdapat di dalamnya file XML dan xsd

File XML digunakan untuk membuat struktur awal dari beberapa data.
Dan xsd digunakan untuk mengecek apakah struktur XML yang kita buat well form dan validasinya berhasil.

Langkah-langkah yang harus dilakukan
1. Buatlah project baru dengan memilih menu file->new->project->plugin in project lalu buat nama pendidikan
2. Pada package yang telah dibuat klik kanan pilih other->folder XML-> XML file-> beri nama pendidikan.XML->ok
3. Setelah file XML berhasil dibuat isi data sesuai yang diinginkan atau seperti praktik yang saya lakukan yang berisi data mahasiswa dan jurusannya
4. Setelah selesai membuat file XML klik kanan pada file XML->create XML definition-> pilih XML schema->dan beri nam file dengan format xsd
   contoh pendidikan.xsd
5. File xsd sudah terbentuk tanpa harus mengoding ataupun membuat lagi, namun kita harus melink kan XML file dengan xsd file.
   klik kanan pada xsd file lalu pilih generate->XMLfile-> lalu akan terbentuk link dari XML file yang akan di copy pada XML master atau
   yang pertama kita buat.
6. Lalu copy kan coding dari XML yang hasil generate pada XML pertama yang kita buat pada struktur/tag utama lalu save
7. setelah bisa di validasi. kita membuat agar file email yang kita buat harus menggunakan tanda @ dan .
8. pilih struktur email di xsd lalu pilih constraint dan pattern lalu pilih add dan buat agar tanda @ . harus ada pada file yang di jalankan. 
   setelah selesai pilih save.
9. Uji sekali lagi pada file XML pertama yang dibuat jika sudah berjalan maka praktik  sudah berhasil


Demikianlah langkah-langkah cara pengerjaan file xsd pada file ml untuk validasi.